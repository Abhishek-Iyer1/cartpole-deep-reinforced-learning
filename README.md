# cartpole-deep-reinforced-learning
We implement a DQN Agent using a Boltzmann Q Policy to tame the Cart Pole problem in the discrete action space. The method is tested against the baseline of making random movements and is implemented using the OpenAI Gym.

The notebook is split into sections and is pretty self explanatory. You can get the following outputs by following the instructions in [CartPole-DRL.ipynb](CartPole-DRL.ipynb)

This is how the baseline method which takes random actions performs.

https://user-images.githubusercontent.com/79250867/114999462-80190e80-9ebf-11eb-8283-089b3c22bd20.mp4


<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="cartpole.png">
    <source src="videos/train.mp4" type="video/mp4">
  </video>
</figure>

Here is how our trained DQN Agent performs.

https://user-images.githubusercontent.com/79250867/114999544-945d0b80-9ebf-11eb-8273-5696b9758c2b.mp4


<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="cartpole.png">
    <source src="videos/test.mp4" type="video/mp4">
  </video>
</figure>
