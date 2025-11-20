# ansible-jobeinabox
Moodle CodeRunner QuestionType Server Jobe (jobeinabox)
based on JobeInABox: https://github.com/trampgeek/jobeinabox

for easy one commandline setup and remove
a good option for locally testing with moodle around on same device
but as well prepared for working in production environment, with optional configurable firewall setup

ansible-playbook -i environments/dev/hosts jobe.yml

ansible-playbook -i environments/prod/hosts jobe.yml (with firewall setup if env in host_vars uses env: prod)

ansible-playbook -i environments/dev/hosts cleanup.yml

