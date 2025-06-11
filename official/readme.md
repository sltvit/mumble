# To create 16 accounts, you need to download [Mumble](https://www.mumble.info/downloads/) and [Virtual Audio Cable](https://vac.muzychenko.net/en/download.htm)


## Mumble
1. Install to default mumble path
2. Create 16 separate folders of installed mumble, for example: `C:\Mumble\Mumble_01\02\03...`
3. Create shortcuts from each folder listed above to your desktop
4. Create a `Configs` folder and create 16 `Mumble_01\02\03-16.ini` files
5. On all created shortcuts, you need to specify the path to the config, in the properties, in the target, so that they are different
```sh 
 --multiple --config "C:\Mumble\Configs\Mumble_01\02\03-16.ini"
```
6. For each new connection, you need to select the Input Device `line1\2\3` from Audio Cable, and in the Configure create a new certificate for each profile
7. Now you can connect all your profiles to server


## Virtual Audio Cable

1. Standard installation in the root
2. In the settings, select how many cables you need and press set
3. 30 minute trial, full subscription 15-50 USD



#### Notes

```sh
 Each time you launch Mumble, you need to select the correct Line1\2\3 and connect the Certificate you created earlier

 Adding passwords to a channel, in an access token
```