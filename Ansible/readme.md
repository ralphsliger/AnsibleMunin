# Configuración de Ansible


Se instalaran  y configuraran estos  2 servicios : 
<ul>
  <li>Apache</li>
  <li>Munin</li>
  
</ul>

<h3>Primer paso, instalación del servidor web</h3>


### Instalacion Apache

utilizamos el siguiente comando en nuestra consola: 

ansible-playbook -i hosts install_apache.yml


<h2>Instalacion de Munin</h2>

### Instalación Munin

utilizamos el siguiente comando en nuestra consola : 

ansible-playbook -i hosts install_munin.yml
