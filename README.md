## mini-DeXter

one paragraph of project description

## Gettijng Started

how to copy project and get it running on your local machine(s) for development
and testing purposes. Deployment section is for live systems, this one if for
dead systems.

### Prerequisites
Grab your favoroite flavor of light weight raspberry compliant Debian.
This image will be copied over to your mini SD card. Expect the download to be
aout 300 MB.

```
wget https://downloads.raspberrypi.org/raspbian_lite_latest
```

Copy the file 99-pololu.rules to /etc/udev/rules.d in order to grant permission
for all users to use Pololu USB devices
```
cd /etc/udev/rules.d
sudo ~/Downloads/pololu-usb-sdk/99-pololu.rules 99-pololu.rules
sudo udevadm control --reload-rules
```
You'll need some additional libraries from outside this repo as well

```
apt-get install libusb-1.0-0-dev
```

and also

For mono development

```
sudo apt-get install mono-devel
```

### Installing
step by step series of examples
```
Give Examples
```
repeat

```
more examples
```
keep repeating
```
until you're finished
```
end with example of getting data out of system or using it for some demo.

## Running the tests
how do you automate tests for this system

### break down into end to end tests
Explain what test tests
```
example
```

## Deployment
Add additional notes on how to deply on a live system
## Built With

*[title](www.google.com) - string explaining
*[yahoo](www.yahoo.com) - string with description

## Contributing
Please read [CONTRIBUTING.md](www.google.com) for details on code of conduct,
process, and how to submit/pull requests to us.

## Versioning

We used ... for versioning.

## License
This project is licsened under...

## Acknowledgements
* Hat tip to anyone who's code was used
* Inspiriation
* etc

