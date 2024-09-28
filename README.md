# dkms-hid-nintendo

A Nintendo HID kernel module.

For any questions or bug reports, please refer to [hid_nintendo](https://github.com/DanielOgorchock/linux).

## with this patch

- [3rd Party Joycon Compatibility #40 by dietolive-tw](https://github.com/DanielOgorchock/linux/issues/40#issuecomment-2029009734)

## Installation

Install it from source with:

```
git clone https://github.com/cawa0505/dkms-hid-nintendo
cd dkms-hid-nintendo

sudo dkms add .
sudo dkms build nintendo -v 3.2
sudo dkms install nintendo -v 3.2
```


## Related projects

- [joycond](https://github.com/DanielOgorchock/joycond): A userspace daemon to
  combine joy-cons from the hid-nintendo kernel driver
- [joycond-cemuhook](https://github.com/joaorb64/joycond-cemuhook): Support for
  cemuhook's UDP protocol for joycond devices
