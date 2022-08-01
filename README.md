![image](https://user-images.githubusercontent.com/86588827/181847386-389eadcd-de4a-421b-908d-e31edc646657.png)



![GitHub watchers](https://img.shields.io/github/watchers/edgeEngine/edgeengine-linux-arm?style=social)![Discord](https://img.shields.io/discord/1002391068773457980)


# edgeEngine for Linux on ARM

## edgeEngine for Linux ARM Platform 

For those who are new to edgeEngine, we recommend to read about overall capabilities of this product [here](https://devdocs.mimik.com/introduction)


Please also be advised that there are different version of edgeEngine available for different CPU architecture and OS platforms. Please see [here](https://github.com/edgeEngine)

The edgeEngine 3.0.x Runtime for ARM CPU architecture is a new generation of edgeEngine with a new set of features and capabilitis as described in the followings:

 - Supporting WebAssembly serverless microservice runtime environment.
 - Supporting wasi_snapshot_preview1 in WebAssembly serverless microservice runtime environment
 - Supporting Prometheus metrics endpoint. (observability)

 Besides the above mentioned new features, we also imporved the following existing features as described below:
 - Global discovery
 - Feedbacks for API errors
 - Response time in JavaScript serverless microservice runtime environment enabling a serverless enviroenment for different cores of ARM CPU.
 
 By using existing and the new edgeEngine's capabilities, embeded platform developers will be able to: 
 
 - Develop Multi-thread programs cross all cores.
 - Dynamically configure microsercices.
 - Reuse the microservices code cross different platforms.
 - Use RESTful API to communicate with microserces across the CPU cores and across the PCBs.
 - Use a uniform deployement mechanism cross all CPU cores and across different PCBs
 - Dynamically update microservices across the cores, platforms and PCBs.
 - Dynamically deploye microservices across all platforms and PCBs, using "Controll node" and "Worker node" model.
 - Make File system available for all microservices even for those which are running on restricted cores (i.e. R5F cores on TI-TDA4VM)
 - From microservice mesh acorss CPU cores, platfroms or PCBs
 - Enable microservice-to-microservice communication running on CPU cores or beteen PCBs.
 - RESTful API instead of RPC API on restricted ARM coretex (i.e. R5F)

 ## Compatibility

#### TI....


| CPU Architecture | CPU Type   | Operating System| edgeEngine Artifact |
| :-------- | :------- | :-------- | :-------- |
| ARM A72, A73  | xxxxxxxxxxxx | xxxxxxxxxxxx | xxxxxxxxxxxx | 
| |  xxxx  | xxxxxxxxxxxx | xxxxxxxxxxxx | xxxxxxxxxxxx | 
|  | xxxxxxxxxxxx | xxxxxxxxxxxx | xxxxxxxxxxxx | 
|  | xxxxxxxxxxxx | xxxxxxxxxxxx | xxxxxxxxxxxx | 

## Related

What are the relates (internal and external) Sources ? 
- [QNX](https://www.qnx.com/developers/docs/)
- [Ubuntu](https://ubuntu.com/desktop/developers)

## How does it work ?

- A generic diagram ?

## Documentation 

<details><summary> Installation Guide </summary>
<p>
 
1. Download latest release for Ubuntu [HERE](https://github.com/edgeEngine/edgeengine-linux/releases)
 
2. Create new directory
 
3. Move package to newly created directory 
 
4. Open terminal and navigate to the newly created directory that now has the downloaded .tar file
 
5. *Untar package (ex:)
 
```
tar xvf edge-linux-v3.0.0.tar
```
6. Run start script to start edgeEngine
```
./start.sh
```
7. Please visit https://developer.mimik.com and create your account and get more information


</p>
</details>

<details><summary> Note: </summary>
<p>



* A directory may be made after untaring. Navigate into that directory to find `start.sh` script 
- Do not close terminal window where edgeEngine is running. Closing this window will terminate edgeEngine process
- To stop edgeEngine simply close or use keyboard shortcut CTRL + C in terminal window where edgeEngine is running
"Hello World"


</p>
</details>


## Contact


[Email](edgifi@mimik.com)

[Discord](https://discord.gg/vrdXc5MM)

## Contributing 
We Always welcome contribution. Refer to our contribution guideline.

## Community 

 [Join us in Discord](https://discord.gg/vrdXc5MM)



