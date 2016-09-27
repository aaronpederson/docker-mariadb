FROM aaronpederson/ubuntu

RUN ansible-galaxy install telusdigital.mariadb
COPY playbook.yml /etc/
RUN ansible-playbook /etc/playbook.yml

