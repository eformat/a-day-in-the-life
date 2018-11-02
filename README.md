# a-day-in-the-life

Login to openshift using `oc login` then run

```bash
ansible-playbook -vv main.yaml --extra-vars token=$(oc whoami -t) --step
```

