# AI-deck examples repository 
## This repo is forked from te original one, this one contains modified wifi-streaming example (in examples/other) that sets up desired framerate and has a UDP client, which should be used to receive image when AI deck is setup to communicate with UDP protocol
> To obtain the image from the AIDeck change the ESP32_IP in udp_client.py. You can check the IP Address of the AIdeck in router manager webpage.
> ⚠️ Important Notice: The GreenWaves Technologies website is down, preventing fetching and compiling the autotiler. This means that deploying neural networks through [gap_sdk](https://github.com/GreenWaves-Technologies/gap_sdk) or the Docker image is not possible unless you already have the file. However, you can still deploy neural networks using [DORY](https://github.com/pulp-platform/dory) as an alternative.
>
> For more details, updates and workarounds, see the announcement [here](https://github.com/orgs/bitcraze/discussions/1854).

Check out the [documentation](https://www.bitcraze.io/documentation/repository/aideck-gap8-examples/master/)
for starting guides.
