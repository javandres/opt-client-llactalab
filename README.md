# OpenTripPlanner Standard UI

## Description

Official OTP user interface, deployable with docker-compose 

View live in http://201.159.223.152/otpui/

## Getting Started

1. In the `js/otp/config.js` find and replace "hostname" with the OTP api url:

    > "hostname : "http://myotp.api:port"

2. Run with docker-compose:

    ```bash
    git clone https://github.com/llactalab/otp-client-llactalab
    docker-compose up
    ```
