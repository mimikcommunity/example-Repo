# Title

![image](https://user-images.githubusercontent.com/86588827/181847386-389eadcd-de4a-421b-908d-e31edc646657.png)
![GitHub forks](https://img.shields.io/github/forks/mimikcommunity/example-Repo?style=for-the-badge)
![GitHub watchers](https://img.shields.io/github/watchers/mimikcommunity/example-repo?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/mimikcommunity/example-repo?style=for-the-badge)
![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![Community](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
<ol>
  <li>  <a href="#About">About</a> </li>
  <li> <a href="#prerequisites">prerequisite</a> </li>
  <li>  <a href="#Compatibility">Compatibility</a> </li>
  <li>  <a href="#Instructions">Instructions</a> </li>
  <li>  <a href="#Related">Related</a> </li>
  <li>  <a href="#Notes">Notes</a> </li>
  <li>  <a href="#Community-&Support">Community & Support</a> </li>
  
 
  </ol>
       
</details>

## About
In this document you will be able to : 

- to install and run edgeEngine on a Linux system for ARM and X86 Platforms

## prerequisites


For those who are new to edgeEngine, we recommend reading about the overall capabilities of this product [here](https://devdocs.mimik.com/introduction)


Please also be advised that different versions of edgeEngine are available for different CPU architectures and OS platforms. Please see [here](https://github.com/edgeEngine)

The edgeEngine 3.0.x Runtime for ARM CPU architecture is a new generation of edgeEngine with a new set of features and capabilities as described in the followings:

 - Supporting WebAssembly serverless microservice runtime environment.
 - Supporting wasi_snapshot_preview1 in WebAssembly serverless microservice runtime environment
 - Supporting Prometheus metrics endpoint. (observability)

 Besides the above-mentioned new features, we also improved the following existing features as described below:
 - Global discovery
 - Feedbacks for API errors
 - Response time in JavaScript serverless microservice runtime environment enabling a serverless environment for different cores of ARM CPU.
 
 By using existing and the new edgeEngine's capabilities, embedded platform developers will be able to: 
 
 - Develop Multi-thread programs across all cores.
 - Dynamically configure microservices.
 - Reuse the microservices code across different platforms.
 - Use RESTful API to communicate with microservices across the CPU cores and across the PCBs.
 - Use a uniform deployment mechanism across all CPU cores and across different PCBs.
 - Dynamically update microservices across the cores, platforms, and PCBs.
 - Dynamically deploy microservices across all platforms and PCBs, using the "Control node" and "Worker node" model.
 - Make the File system available for all microservices, even for those which are running on restricted cores (i.e., R5F cores on TI-TDA4VM).
 - From microservice mesh across CPU cores, platforms, or PCBs.
 - Enable microservice-to-microservice communication running on CPU cores or between PCBs.
 - RESTful API instead of RPC API on restricted ARM cortex (i.e., R5F)

 ## Compatibility



| CPU Architecture | CPU Type   | Operating System| system |
| :-------- | :------- | :-------- | :-------- |
| ARMv8-A| Cortex-A34, Cortex-A35, Cortex-A53, Cortex-A57, Cortex-A72, Cortex-A73|TI-Linux     | https://github.com/edgeEngine/edgeengine-linux-arm| 
|ARMv8-A | Cortex-A34, Cortex-A35, Cortex-A53, Cortex-A57, Cortex-A72, Cortex-A73  |Ubuntu Linux  | https://github.com/edgeEngine/edgeengine-linux-arm| 
|  ARMv8-A| Cortex-A34, Cortex-A35, Cortex-A53, Cortex-A57, Cortex-A72, Cortex-A73| NVIDIA Linux | https://github.com/edgeEngine/edgeengine-linux-arm| 
|ARMv8-A  |  Cortex-A53, Cortex-A72       | QNX 7.1  | https://github.com/edgeEngine/edgeengine-embedded-os | 



## Instructions 

<details><summary> Installation Guide </summary>
<p>
 
1. Download the latest release for Ubuntu [HERE](https://github.com/edgeEngine/edgeengine-linux/releases)
 
2. Create a new directory
 
3. Move the package to newly a created directory 
 
4. Open a terminal and navigate to the newly created directory that now has the downloaded .tar file
 
5. *Untar package (ex:)
 
```
tar xvf edge-linux-v3.0.0.tar
```
6. Run start script to start edgeEngine
```
./start.sh
```
7. Please visit https://developer.mimik.com and create your account and access the resources


</p>
</details>

<details><summary> Note: </summary>
<p>


* A directory may be made after untaring. Navigate into that directory to find `start.sh` script 
- Do not close the terminal window where edgeEngine is running. Closing this window will terminate edgeEngine process.
- To stop edgeEngine, simply close or use the keyboard shortcut CTRL + C in the terminal window where edgeEngine is running "Hello World."


</p>
</details>

## Related

What are the related (internal and external) Sources ? 
- [QNX](https://www.qnx.com/developers/docs/)
- [Ubuntu](https://ubuntu.com/desktop/developers)


## Notes 

## Community & Support 

