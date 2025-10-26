# Simulando-um-Ataque-de-Brute-Force-de-Senhas-com-Medusa-e-Kali-Linux
Nessa atividade simulei um ataque de Brute Force utilizando o Medusa no Kali Linux

Para realizar a atividade utilizei o Kali Linux e o Metasploitable 2

# Segui o siguinte passo a passo:

1 - Criei um lista de login e senha </br>
<img width="1366" height="662" alt="1-criando lista de login e senhas" src="https://github.com/user-attachments/assets/318853bf-5682-42d2-af3e-1b39f8324bcf" />

2 - Copiei a senha utilizando o Medusa no Kali Linux </br>
<img width="1366" height="662" alt="2-captura de senha utilizando MEDUSA" src="https://github.com/user-attachments/assets/bf3400c9-4553-476b-aad5-dbc38cd34cae" />

3 - Utilizei o Medusa para simular a combinação de usuários e nenhas</br>
<img width="1366" height="662" alt="3-utilizando o MEDUSA para simular combinacao de usuarios e senhas" src="https://github.com/user-attachments/assets/e2dcaaa3-4861-42c5-b821-5e02947fdcb8" />

<img width="1366" height="662" alt="4-utilizando o MEDUSA para simular combinacao de usuarios e senhas parte 2" src="https://github.com/user-attachments/assets/0d88cfc2-d470-4e99-8246-57f05dae0a1c" />

<img width="1366" height="662" alt="5-utilizando o MEDUSA para simular combinacao de usuarios e senhas parte 3" src="https://github.com/user-attachments/assets/88e633be-c62f-4672-9944-dc069bd2c271" />

4 - Realizei um ataque em cadeia, enumeração smb + password sprayng</br>
<img width="1366" height="662" alt="6-realizando enumeracao de um ambiente mal configurado" src="https://github.com/user-attachments/assets/33280f02-40ed-4d5a-816d-4d9622ec52aa" />

<img width="1366" height="662" alt="7-abrindo o comando para enumeracao" src="https://github.com/user-attachments/assets/3ffc3ff1-9248-4c41-b959-dc69b787599e" />

<img width="1366" height="662" alt="8-dentro do enum" src="https://github.com/user-attachments/assets/2027fa3c-a165-4ec5-a8ce-7ea22156434e" />

Nesse momento tive acesso a todos os usuários 
<img width="1366" height="662" alt="9-lista de usuarios no comando enum" src="https://github.com/user-attachments/assets/69ed90df-b861-4402-9948-e0493eb6af7f" />

5- Nesse momento simulei um cenário de ambiente corporativo mal configurado. </br>
Aqui criei uma lista de usuário</br>
<img width="1366" height="662" alt="10-Criando lista de usuarios" src="https://github.com/user-attachments/assets/617acc62-b39c-45eb-8cab-cb1371124230" />

6- Testei o acesso via smbclient</br>
<img width="1366" height="662" alt="11-Testando o acesso com smbclient" src="https://github.com/user-attachments/assets/7ea75bd2-4942-427e-a536-0e38bfca7b24" />

Acessando assim a máquina vulnerável na rede corporativa mal configurada.



