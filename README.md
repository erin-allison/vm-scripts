# VM Scripts

Some scripts for managing the libvirtd VMs on my network.

### Usage

#### launch-vm

```bash
./launch-vm $SERVER $RELEASE $NAME $GROUP $IP $GW [$KEY]

./launch-vm erin-room-router hirsute k8s-master dev 172.30.1.11/24 172.30.1.254
```

#### load-template
```bash
./load-template $URL $SNAPSHOTTAG

./load-template https://cloud-images.ubuntu.com/hirsute/20210623/hirsute-server-cloudimg-amd64.img 20210623
```
