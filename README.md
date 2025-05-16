# NT132.P21.ANTN-Data-Management-Platform-Trino

### Turtorial
- Youtube: [link](https://www.youtube.com/watch?v=gAqYkR2oGgM)
- Document: [link](https://deploy-preview-229--trino.netlify.app/episodes/20.html)

### Download:
- IntelliJ IDEA Community Edition (free version): [link](https://www.jetbrains.com/idea/download/download-thanks.html?platform=windows&code=IIC)
- Install Git
- Install Docker
- Trino: fork from https://github.com/trinodb/trino
 ### Setup docker
 - Enable Virtual Machine Flatform: Mở powershell as 


- Bước 1: Kiểm tra và bật thủ công "Virtual Machine Platform"
```Shell
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform -All
```
- Bước 2: Khởi động lại dịch vụ WMI và BITS
```Shell
net stop winmgmt /y
net stop bits
net start winmgmt
net start bits
Enable-WindowsOptionalFeature -Online -FeatureName VirtualMachinePlatform -All
```
- Bước 3: Khởi động lại máy tính: Kiểm tra
```Shell
Docker info
```
- 
