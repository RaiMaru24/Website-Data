Each of the device is written as an object. Consider using this template to add/update data:

## Template for devices

> devices/data/devices.json

```json
{
	"id": 1, // increase the id number by 1 to last id value
	"name": "Redmi Note 10 Pro",
	"codename": "sweet",
	"imageUrl": "https://raw.githubusercontent.com/GenesisOS/Website-Data/main/devices/images/redminote10pro.png",
	"maintainer": "Alen24",
	"buildDate": "29 Sept 2023"
}
```

Make sure the last added key-value or object does not end with a comma

## Template for each specific device:

> e.g., devices/list/alioth.json

```json
{
	"id": 1,
	"name": "Poco F3/Mi 11x 5G",
	"codename": "alioth",
	"imageUrl": "https://images.pling.com/img/00/00/68/21/39/1917153/poco-f3.jpg",
	"maintainer": "Nerd",
	"buildDate": "29 Sept 2023",
	"oem": "Xiaomi",
	"download": "https://www.pling.com/p/1917153/",
	"supportGroup": "",
	"donate": "",
	"olderBuilds": "https://sourceforge.net/projects/protonplus/files/Tiramisu/alioth/"
}
```

Make sure the last added key-value or object does not end with a comma

## Regarding cl_branch.json:

This is only meant to provide branchName value to changelog URL. Please only change it if the changelog repo contains a new branch (related to a new android release).
