# Internet-of-Things-Smart-Water-Meter-Monitoring-Platform-Unauthorized-RCE
The IoT smart water meter monitoring platform affiliated to Shandong Kede Electronics Co., Ltd. has an unauthorized remote code execution (RCE) vulnerability

# FINGER
```
title = "物联网智能水表监管平台"
```

# info
```
CVE-ID: CVE-2025-63624
affected version: V1.0
```

# Official website of Shandong Kede Electronics Co., Ltd
domain:http://www.sdkede.com/
<img width="1735" height="885" alt="图片" src="https://github.com/user-attachments/assets/ae425449-8955-4bf7-9ae5-8fb4bc987391" />

# Details of the vulnerability
Homepage of the IoT Smart Water Meter Monitoring Platform
<img width="1611" height="751" alt="图片" src="https://github.com/user-attachments/assets/0003036f-9193-4ca9-a2fc-e32515fbe99d" />

The vulnerability exists in the txtJZRQ parameter of the query function in the unauthorized page /kddz/imei_list.aspx
<img width="1910" height="215" alt="图片" src="https://github.com/user-attachments/assets/a20387d8-3ed3-4f96-8a5b-4efe72b595ec" />

injection delay payload
<img width="1556" height="755" alt="图片" src="https://github.com/user-attachments/assets/a5bf31d3-c25b-439b-97ca-f0c39909b5d7" />

Enable the xp_cmdshell stored procedure,The string 'EXEC' is filtered by the system, but it can be bypassed using 'eXeC'
<img width="1504" height="672" alt="图片" src="https://github.com/user-attachments/assets/6b95e3a3-1206-4fa4-bf41-9fb96efe2515" />

Execute the ping command to obtain DNS logs
<img width="1506" height="594" alt="图片" src="https://github.com/user-attachments/assets/e30637d9-009a-4c5b-87db-ad3f517fcde9" />

<img width="1522" height="67" alt="图片" src="https://github.com/user-attachments/assets/1ca11fe3-daec-4848-9891-0f9240e94600" />
