
<center><h1 class="rsection"><b>Bipedal walking robot using Deep Deterministic Policy Gradient</b></h1></center>

<center><h2><b>Computational Intelligence Laboratory, Aerospace Engineering Division, IISc.</b></h2></center>

<div class="container-fluid">
  <div class="row">
    <!-- <div class="col-md-6">
        <img class="rimg" src="{{ site.github.url }}/media/biped_trained.gif" />
    </div> -->
    <div class="col-md-12">
        <!-- <h3 class="rtitle"><b>Bipedal walking robot using Deep Deterministic Policy Gradient.</b></h3> -->
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        Machine learning algorithms have found several applications in the field of robotics and control systems. The control systems community has started to show interest towards several machine learning algorithms from the sub-domains such as supervised learning, imitation learning and reinforcement learning to achieve autonomous control and intelligent decision making. Amongst many complex control problems, stable bipedal walking has been the most challenging problem.</p> 
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        The autonomous stable walking of the planar bipedal walker in simulation environment is achieved using <strong>Deep Deterministic Policy Gradient(DDPG)</strong> based on an <strong>actor-critic learning framework</strong> [for continuos action space]. 
        </p>
        <br>
        <center>
            <div class="image-wrapper">
                <a class ="image-popup" href="https://nav74neet.github.io/media/blog/ac_network.jpg" title="ACN">
                    <img src="https://nav74neet.github.io/media/blog/ac_network.jpg" alt="ACN" align="middle">
                </a>
            <center>
                <p class="image-caption" style="font-size:14px; text-align: center;">
                    Fig.1 Actor-Critic Learning network.
                </p>
            </center>
            </div>
        </center>
        <br>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        The <b>State space</b> includes <b>robot joint angles</b>, <b>joint angular velocities</b>, <b>waist height</b>, etc. The <b>action space</b> covers the predicted <b>joint torques</b>.</p>
        <br>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        <center>
            <div class="image-wrapper">
                <a class ="image-popup" href="https://nav74neet.github.io/media/biped_training.gif" title="DDPG">
                    <img src="https://nav74neet.github.io/media/biped_training.gif" alt="DDPG" style="border:2px solid black;" align="middle">
                </a>
            <center>
                <p class="image-caption" style="font-size:14px; text-align: center;">
                    Fig.2 Learning to walk - initial baby steps.
                </p>
            </center>
            </div>
        </center>
        <br>    
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        The robot demonstrates successful walking behaviour by learning through several of its trial and errors, <b>without any prior knowledge of itself or the world dynamics</b>. After training the model in simulation, it was observed that, with a <b>proper shaped reward function</b>, the robot achieved faster walking or even rendered a running gait with an average speed of 0.83 m/s [see Fig.2]. The gait pattern of the bipedal walker was compared with the actual human walking pattern. The results show that the bipedal walking pattern had similar characteristics to that of a human walking pattern.</p>
        <br>
        <center>
            <div class="image-wrapper">
                <a class ="image-popup" href="https://nav74neet.github.io/media/trained.gif" title="DDPG">
                    <img src="https://nav74neet.github.io/media/trained.gif" alt="DDPG" style="border:2px solid black;" align="middle">
                </a>
            <center>
                <p class="image-caption" style="font-size:14px; text-align: center;">
                    Fig.3 Stable Bipedal walking robot.
                </p>
            </center>
            </div>
        </center>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
            <b>References:</b> 
            <ol style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
                <li>Lillicrap, Timothy P., et al.<b>Continuous control with deep reinforcement learning.</b> arXiv preprint arXiv:1509.02971 (2015).[<a href="https://arxiv.org/abs/1509.02971">pdf</a>]</li>
                <li>Silver, David, et al.<b>Deterministic Policy Gradient Algorithms.</b> ICML (2014).[<a href="http://proceedings.mlr.press/v32/silver14.pdf">pdf</a>]</li>
            </ol>
        </p>
        <br>
        <p style="text-align:justify; font-family: 'Merriweather', 'Hiragino Sans GB', 'Microsoft YaHei', 'WenQuanYi Micro Hei', sans-serif;">
        <a href="https://github.com/nav74neet/ddpg_biped" class="md-link btn-default btn rbtn">Code</a>
        <a href="https://arxiv.org/abs/1807.05924" class="md-link btn-default btn rbtn">Paper</a>
        <a href="https://www.youtube.com/watch?v=Q4N78P7cink" class="md-link btn-default btn rbtn">Video</a>
        </p>
    
<br>