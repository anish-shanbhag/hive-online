# hive-online
Hive Online is an online implementation of the board game [Hive](https://en.wikipedia.org/wiki/Hive_(game)). It is similar to something like chess in that it is an abstract strategy board game with pieces that can move, but the main difference is that there's no board in Hive.

You can play the game online at https://anish-shanbhag.github.io/hive-online/.

# Technologies Used
Hive Online is made using Vue.js, a JavaScript framework. It also uses the PeerJS library for setting up a peer-to-peer connection between players in real time.

# Demo Images
Below are some images from the game. You're greeted with a welcome screen upon going to the site:

<img src="https://anish-shanbhag.github.io/hive-online/demo/welcome.png" width="400px">

Then, you are prompted to choose an ID, which will be used to identify you in a peer-to-peer connection.

<img src="https://anish-shanbhag.github.io/hive-online/demo/choose-id.png" width="400px">

You can choose to either join or host a game:

<img src="https://anish-shanbhag.github.io/hive-online/demo/host-or-join.png" width="400px">

Depending on which option you chose, you need to either enter the ID of the player you want to join, or wait until someone else joins you.

<img src="https://anish-shanbhag.github.io/hive-online/demo/join.png" width="400px">
<img src="https://anish-shanbhag.github.io/hive-online/demo/host.png" width="400px">

Once the host receives a request to join, they can either choose to accept or decline it:

<img src="https://anish-shanbhag.github.io/hive-online/demo/accept-request.png" width="400px">

Finally, once the request is accepted, the game starts. Below are some images from various points in a sample game.

<img src="https://anish-shanbhag.github.io/hive-online/demo/early-game.png" width="400px">
<img src="https://anish-shanbhag.github.io/hive-online/demo/mid-game.png" width="400px">
<img src="https://anish-shanbhag.github.io/hive-online/demo/late-game.png" width="400px">

Once a player wins by surrounding an opponent's Queen Bee with pieces, the game ends and each player is shown who won.

<img src="https://anish-shanbhag.github.io/hive-online/demo/win.png" width="400px">