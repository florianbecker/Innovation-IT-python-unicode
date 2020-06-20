# Innovation IT python unicode
Innovation IT NVMe firmware has issue with python unicode interpreter

# NVMe-cli
```bash
root@test5:~# nvme list
Node             SN                   Model                                    Namespace Usage                      Format           FW Rev  
---------------- -------------------- ---------------------------------------- --------- -------------------------- ---------------- --------
/dev/nvme0n1     AA000000000000000131 INNOVATION��IT                           1         512,11  GB / 512,11  GB    512   B +  0 B   S0614B0G
```
As you can see, there are two signs or multibyte char with defect unicode output.

# This project

## Install python example
```python
```

## Run python example
```bash
```

# Result
- Linux systems like Ubuntu or RHEL, use a graphical installer and except because of this unicode signs.
- You are not able to install a system, only without installer of Ubuntu. I was not able to install RHEL in any case.
- The company behind Innovation IT products needs to update thier firmware and remove these unicode signs from model to work probably and even more correct.
- If you plan to buy a system with these NVMe, only do it if you not want to tun linux as the host system.

