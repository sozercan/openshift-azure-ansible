# openshift-azure-ansible


`git clone -b openshift https://github.com/sozercan/ansible.git`

```
pip install --upgrade pip
pip install --upgrade setuptools
pip install .[azure]
source ./hacking/env-setup
pip install -r ./requirements.txt
make install
```

```
export AZURE_SUBSCRIPTION_ID="<...>"
export AZURE_CLIENT_ID="<...>"
export AZURE_SECRET="<...>"
export AZURE_TENANT="<...>"
```

`ansible-playbook main.yaml`
