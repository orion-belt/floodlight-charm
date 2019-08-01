Get this charm at Juju charm store https://jaas.ai/u/rohan-kharade/floodlight/4

#### 1. Set up Juju environment

For how to setup Juju, refer wiki page
https://github.com/orion-belt/floodlight-controller/wiki

#### 2. Deploy directly from Juju charm store
```
juju deploy cs:~rohan-kharade/floodlight-4
```

##### OR
#### 2. Clone repo and deploy as local charm
```
git clone https://github.com/orion-belt/floodlight-controller.git
juju deploy ./floodlight-charm
```

#### 3. Test and verify install
You can use following command to check installation process
```
watch juju status --relations 
```
After successfull installation of charm, you will see "Running floodlight" message. <br/>
Now you can also access controller UI as below <br/>
`https://<controller_ip>:8080/ui/index.html`
