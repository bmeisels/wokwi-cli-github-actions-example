# Wokwi CLI Github Actions Example

This repository contains a Zephyr "Hello World" example to demonstrate use of Wokwi CLI with Github Actions

# Local Setup
    source ~/zephyrproject/.venv/bin/activate
    mkdir workspace
    cd workspace
    git clone https://github.com/bmeisels/wokwi-cli-github-actions-example.git
    west init -l wokwi-cli-github-actions-example
    west update
    cd wokwi-cli-github-actions-example/app
    west build -b esp32c3_devkitm .