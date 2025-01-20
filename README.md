# Anndroid_GoolgeATS
安装简略流程和命令
1.install ats :
```
      address:https://source.android.com/docs/core/tests/development/android-test-station/ats-user-guide?hl=zh-cn#install-with-installer
      command:curl https://storage.googleapis.com/android-mtt.appspot.com/prod/install.sh | bash
```

2.install google cloud:
```
    address:https://cloud.google.com/sdk/docs/install#deb
    command:sudo apt-get update && sudo apt-get install google-cloud-cli
            sudo snap install google-cloud-cli --classic
    init:gcloud init
```

3.ats init and start:
```
    adb kill-server
    mtt -vv start --port [9000]
```
4.ats test config(gms.yaml):
```
    address:https://docs.partner.android.com/gms/testing/overview/test-station?hl=en
    command:gsutil cp gs://android-test-catalog/prod/gms.yaml gms.yaml
```
