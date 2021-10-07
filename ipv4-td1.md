# ipv6-td1

## Adressage IPv6

### Question 1
*Comprimez les adresses IPv6 suivantes*

- *2001:0001:0002:014E:F140:0102:8012:00AE*
  
  >**2001:1:2:14E:F140:102:8012:AE**
- *2001:0120:0000:0000:01A3:0102:8765:A00F*
  
  >**2001:120:0:0:1A3:102:8765:A00F**
- *2001:0120:0000:0000:01A3:0000:8765:A00F*
  
  >**2001:120:0:0:1A3:0:8765:A00F**
- *0000:0000:0000:0000:0000:0000:0000:0001*
  
  >**::1**
  
### Question 2
*Explosez les adresses IPv6 suivantes*

- *2001:14C8::871:206:A14:23*
  
  >**2001:14C8:0000:0871:0206:0A14:0023**
- *2002:203::AEF:12:0:1B1:1*
  
  >**2003:0203:0000:0AEF:0000:01B1:0001**

### Question 3
Quelles adresses IPv6 sont valides ?

- *2001:14C8::871:206:A14:23*

  >**Oui**

- *2001:14C8::871:206::A14:23*

  >**Non car deux fois des deux-points**

- *2001:14C8:0:0134::A120:E001*

  >**Oui**

- *200F:23G5:23:1:45:A234::1*
  
  >**Non car G**

### Question 4
*Donner la(es) réponse(s) correspondant à la compression des adresses IPv6 ci-dessous*

- *2001:0db8:0000:0000:0000:0000:0000:0c50*

  >**2001:0db8:0:0:0:0:0:0c50**<br>
  >**2001:0db8::0c50**<br>
  >**2001:db8::c50**<br>
  >~~2001:db8::c5~~

- *2001:0db8:0000:0000:b450:0000:0000:00b4*

  >~~2001:db8::b450::b4~~<br>
  >**2001:db8::b450:0:0:b4<br>
  >2001:db8::b45:0000:0000:b4<br>
  >2001:db8:0:0:b450::b4**

- *2001:0db8:00f0:0000:0000:03d0:0000:00ff*
  >2001:0db8:00f0::3d0:0:00ff<br>
  >2001:db8:f0:0:0:3d0:0:ff<br>
  >2001:db8:f0::3d0:0:ff<br>
  >2001:0db8:0f0:0:0:3d0:0:0ff

- *2001:0db8:0f3c:00d7:7dab:03d0:0000:00ff*
  >~~2001:db8:f3c:d7:7dab:3d:0:ff~~<br>
  >**2001:db8:f3c:d7:7dab:3d0:0:ff<br>
  >2001:db8:f3c:d7:7dab:3d0::ff**<br>
  >~~2001:0db8:0f3c:00d7:7dab:03d::00ff~~

### Question 5
*Donnez le numéro de réseau et l’adresse MAC d’origine des adresses suivantes*

- *2001:0660:2402:1001:208:2ff:fedc:633/48* 
    - Numéro de réseau
    >**2001:0660:2402::/48**
    - MAC
    >**00-08-02-DC-06-33**
    
- *2001:0660:F402:1000:3e52:82ff:feea:5bd2/64*
    - Numéro de réseau
    >**2001:0330:F402:1000::/64**
    - MAC
    **3C-52-82-EA-5B-D2**












