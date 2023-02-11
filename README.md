基于oznu/cloudflare-ddns修改而而来，主要增加了企业微信应用通信 使用-e指定微信参数：corpid corpsecret agentid即可

修改：/root/etc/cont-init.d/50-ddns
默认是arm64，在Dockerfile修改基础镜像即可

