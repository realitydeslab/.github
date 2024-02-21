# Reality Design Lab

Reality Design Lab is an interdisciplinary research and design lab focused on the intersection of spatial computing and programmable cryptography. Led by [Botao Amber Hu](https://botao.hu)([@botaohu](https://github.com/botaohu)), this lab prioritizes the development of embodied interactions within mixed reality and the realm of blockchain-substrated artificial life. 

Reality Design Lab is non-profit organizations sponsored by [Holo Interactive](https://holoi.com), which is the innovative force behind HoloKit. 

# HoloKit X
* 🥽 **Ingenious Invention**: We have released an optical see-through stereoscopic MR headset [HoloKit X](https://holokit.io) in 2022, which is an award-winning premium-quality upgrade from our original periscope-shaped invention [HoloKit 1](https://1.holokit.io/), a cardboard proof of concept released in 2017.
* 📲 **Full AR Functionalities**: Without reinventing the wheel, our open-source, phone-based MR headset maximizes your smartphone's existing AR functionalities, such as [ARKit](https://developer.apple.com/documentation/arkit/arkit_in_ios), [6DOF Spatial Tracking](https://developer.apple.com/documentation/arkit/arworldtrackingconfiguration), [Hand Tracking](https://developer.apple.com/documentation/vision/detecting_hand_poses_with_vision), [Depth and Mesh by LiDAR](https://developer.apple.com/documentation/avfoundation/additional_data_capture/capturing_depth_using_the_lidar_camera), [Spatial Audio](https://developer.apple.com/documentation/arkit/), and [MultipeerConnectivity](https://developer.apple.com/documentation/multipeerconnectivity).
* 💲 **Accessible Immersion**: With a crystal-clear 60-degree FOV optics, experience a rich, immersive mixed reality that stands as a cost-effective alternative to 20-30x pricier options like [HoloLens](https://www.microsoft.com/en-us/hololens/buy) and [Magic Leap](https://www.magicleap.com/buy-now).
* 🎨 **For Creators by Creators**: Tailored for quick and efficient MR creative project execution, especially in multiplayer scenarios, HoloKit is the go-to tool for *MR researchers, educators, and creators*. See more [#MadeWithHolokit works](https://github.com/holoi/awesome-holokit) from our community.
* 🎖 **Award-winning**: Design of HoloKit X won [Red Dot Award 2023, Product Design](https://www.red-dot.org/project/holokit-x-64930) and [Core 77 Design Award 2023 Consumer Technology](https://designawards.core77.com/consumer-technology/122922/HoloKit-X-Accessible-AR-Copresence) and nominated for [Webby Award 2023](https://winners.webbyawards.com/2023/metaverse-immersive-virtual/metaverse-immersive-features/technical-achievement/249481/holokit-x--a-stereoscopic-ar-headset-for-iphone) and [SXSW Innovation Awards 2023](https://eon-media.com/insights/innovation-awards-at-sxsw-part-one/).

# Getting started 

* Buy HoloKit on [our website](https://holokit.io/products/holokit-x) or [Amazon](https://www.amazon.com/s?i=merchant-items&me=ASBKMHTMFQG2J).
* Download [HoloKit App](https://apps.apple.com/us/app/holokit/id6444073276) to try our demos. 
* Read [Documentations](https://docs.holokit.io/for-creators/unity/overview) to understand how to build a creative MR project based on HoloKit.
* Read [ARFoundation-Samples](https://github.com/Unity-Technologies/arfoundation-samples/tree/main) to skim through the AR capabilities of your phone, consider utilizing them in MR with HoloKit.
* Access to [HoloKit Unity SDK](https://github.com/holoi/holokit-unity-sdk) to build your first HoloKit demo. 

# Getting inspired

Our team is a blend of MR researchers, educators, and creators, making us the quintessential users of HoloKit. Going beyond mere hardware, we are constantly at the forefront of experimenting and pioneering new creative paradigms in MR by leveraging HoloKit. By open-sourcing the majority of our innovations, we aim to inspire more people into the expansive realms of mixed reality.


## Boilerplates

* We created boilerplates for quickly kickstarting your MR project.
   * [HoloKit Singleplayer Boilerplate](https://github.com/holoi/holokit-singleplayer-boilerplate) for simple singleplayer MR experience.
   * [HoloKit Immersal Multiplayer Boilerplate](https://github.com/holoi/holokit-immersal-multiplayer-boilerplate) for co-located multiplayer in fixed scenes (pre-scanning required) with Spectator View using Immersal SDK and  on-based colocation technology. 
   * [HoloKit InstaLocate Multiplayer Boilerplate](https://github.com/holoi/holokit-instalocate-multiplayer-boilerplate) for co-located multiplayer in ad-hoc scenes (pre-scanning NOT required) with Spectator View using Adlocating, an on-device QRCode co-locating technology. 

## Explore more creative MR projects

* We open-sourced our explorative MR creative projects for your inspirations.
  * [Zuzaland](https://github.com/holoi/zuzaland), An innovative experiment aimed at constructing mixed reality monuments for the Network State, recognized and awarded at the hackathon in [Zuzalu](https://zuzalu.city), the world’s first pop-up city founded by [Vitalik Buterin](https://www.palladiummag.com/2023/10/06/why-i-built-zuzalu/).
  * [Becoming Bats](https://github.com/holoi/becoming-bats), an experiment enabling users to mimic bats by casting their voices as ultrasound waves, which are visually transported and reflected onto real-world surfaces through mixed reality.
  * [Talking Olaf](https://github.com/holoi/talking-olaf), a mixed reality experiment that allows users to engage in real-time conversations with Olaf, a beloved Disney character, by utilizing ChatGPT, Voice Recognition, and Artificial Voice Generation technologies.

## Co-located Multiplayer

Co-located Multiplayer represents an unique category in mixed reality scenarios. Utilizing multiple HoloKits provides a cost-effective alternative to using multiple HoloLenses in these scenarios. Moreover, Spectator View, offering a critical tool for capturing and documenting the MR experience from a third-person perspective, is also a special form of co-located multiplayer. Our team is committed to innovatively pushing the boundaries in the realm of co-located multiplayer.

* [Multiplayer Onsite Fighting Arena (MOFA)](https://mofa.ar) is our research project focusing on co-located multiplayer MR game framework for casting magic spells, in which we explored paradigms of competitive, cooperative, asymmetric mixed reality game design strategies crossing handheld and headmounted AR devices. Awarded as the [best interactivity demo](https://www.youtube.com/watch?v=mCHEdItEx2s) in [CHI 2023](https://dl.acm.org/doi/abs/10.1145/3544549.3583935), honorable mention in best demo in ISMAR 2023, and awarded at Flow Hackathon.

Based on our research, we open sourced: 

* [Multipeer Connectivity Transport for Netcode for GameObjects](https://github.com/holoi/netcode-transport-multipeerconnectivity) is a Unity Netcode Transport plugin for Apple Multipeer Connectivity, the tech behind Apple Airdrop, which is tailored for co-located multiplayer MR game to establish the low latency local networking. A synchronized version of this plugin was also merged into [Unity's Multiplayer Community Contributions](https://github.com/Unity-Technologies/multiplayer-community-contributions/tree/main/Transports/com.community.netcode.transport.multipeer-connectivity). See [Sample Project](https://github.com/holoi/netcode-transport-multipeerconnectivity-sample) for kickstarting. 


<!--
* [InstaLocate](https://github.com/holoi/instalocate) is a Unity plugin for an on-device adhoc QRCode co-locating technology. 
-->

