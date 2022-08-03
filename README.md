![image](https://user-images.githubusercontent.com/86588827/181847386-389eadcd-de4a-421b-908d-e31edc646657.png)



![GitHub watchers](https://img.shields.io/github/watchers/edgeEngine/edgeengine-linux-arm?style=social)![Discord](https://img.shields.io/discord/1002391068773457980)


# edgeEngine for Linux on ARM

## edgeEngine for Linux ARM Platform 

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

## Related

What are the related (internal and external) Sources ? 
- [QNX](https://www.qnx.com/developers/docs/)
- [Ubuntu](https://ubuntu.com/desktop/developers)

## How does it work ?

- A generic diagram ?

## Documentation 

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


## Contact


[Email](edgifi@mimik.com)

[Discord](https://discord.gg/vrdXc5MM)

## Contributing 
We Always welcome contribution. [Email](edgifi@mimik.com) us to get more information regarding the contribution guideline. 

## Community 

 [Join us in Discord](https://discord.gg/vrdXc5MM)



