
Run as `ANSIBLE_STDOUT_CALLBACK=debug ansible-playbook -i inventory up.yaml`.

To run a test, use, `ANSIBLE_STDOUT_CALLBACK=debug ansible-playbook -i inventory test.yaml --tags "join"`.

If need debug info, append `-vvv`.