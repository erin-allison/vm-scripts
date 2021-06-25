# VM Scripts

Some scripts for managing the libvirtd VMs on my network.

### Usage

#### launch-vm

```bash
./launch-vm $SERVER $RELEASE $NAME $GROUP

./launch-vm erin-room-router hirsute k8s-master dev
```

#### load-template
```bash
./load-template $URL $SNAPSHOTTAG

./load-template https://cloud-images.ubuntu.com/hirsute/20210623/hirsute-server-cloudimg-amd64.img 20210623
```
