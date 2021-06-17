# Aggregation of variables across hosts into list in ansible

The standard way to do this would be templating, however that
currently doesn't work: https://github.com/ansible/ansible/issues/17806

So this playbook snippit provides an alterative implementation
