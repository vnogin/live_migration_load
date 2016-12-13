ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook load_node_fix.yaml --extra-vars="host_ip=<LOAD_VM_IP> influxdb_ip=1.1.1.1 slice_id=test_slice"

ANSIBLE_HOST_KEY_CHECKING=False ansible-playbook load_node_fix.yaml --extra-vars="host_name=yscb host_ip=<LOAD_VM_IP> host_port=22 host_pass=vagrant influxdb_ip=1.1.1.1 slice_id=test_slice"
