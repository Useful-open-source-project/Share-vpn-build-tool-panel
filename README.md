You can use xui to simply build a vpn or proxy node and panel. It is very simple. After installation, you can set up domain name certificates and the like to ensure the security of the panel. You need to fill in the certificate path in the setting options, then save and restart. xray  Select the latest version, but due to this, although the panel has stopped updating, it can still be used. You can try it first.


Please visit the project, copy the installation script, install the panel with one click, and then build the protocol by yourself. Tutorials will be provided later, and you can study it slowly.

https://github.com/FranzKafkaYu/x-ui/blob/main/README_EN.md




The following similar projects are all based on the xray kernel, all have panel UI interfaces, and are all one-click scripted installations, which are very simple for novice users.



https://github.com/alireza0/x-ui


https://github.com/MHSanaei/3x-ui







It's not the same core, it's a different protocol.



There is a more complex one, and you should be proficient in Linux commands or configurations to use it better.

 https://github.com/apernet/hysteria


 https://v2.hysteria.network/






 To download the corresponding platform or use the client, please visit this branch for detailed instructions.




 https://github.com/Useful-open-source-project/Share-vpn-build-tool-panel/blob/Agent-tool-client/README.md


 X-UI

 We are using vless reality and need a disguised domain name, which can be our own or used on other people's websites. It must support https and then it must support tls 1.3. This is the rigid requirement established by this protocol. When accessing the website domain name, another certificate is required.  The detailed information shows that it supports tls 1.3, which means it is OK.

 Then there is the place to fill in the domain name. Do not change the port of the target website. Just change the domain name. The optional domain name is the certificate of which website you want to apply. Just fill in the domain name. Do not bring the protocol. The network 81 option is selected by default.  TCP, remember to add that user. Under the user option, select flow. Under the option, select xtls-rprx-vision.

 Important things have to be said three times. The firewall port must be allowed to pass before it can be used normally.
