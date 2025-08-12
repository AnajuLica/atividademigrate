# **Tutorial Atividade Migrate**

- Abra o arquivo `php.ini` que está em `xampp/php/php.ini`;
- Procure pelas linhas: `;extension=ftp` `;extension=ffi` `;extension=zip`;
- Remova o ponto e vírgula (`;`) no início de cada uma para ativar as extensões;
- No diretório `xampp/htdocs`, crie uma nova pasta onde ficará seu projeto Laravel.
  
Abra o VisualStudio, selecione a pasta criada, abra o terminal e execute os comandos de instalação do Laravel conforme mostrado  a seguir:


**Passo 1:**  
<img width="247" height="14" alt="ex 1" src="https://github.com/user-attachments/assets/59aa98e9-006a-4ad4-b2db-f46e1f93a1b8" />


**Passo 2:**  
<img width="155" height="15" alt="ex 2" src="https://github.com/user-attachments/assets/71aba07f-729b-4cb7-a8d8-94e869a6c594" />

**Passo 3:** 

<img width="383" height="212" alt="ex 3" src="https://github.com/user-attachments/assets/8fed96fa-d4e9-4478-84b0-3474c094e855" />


**Passo 4:** 

<img width="581" height="220" alt="ex 4" src="https://github.com/user-attachments/assets/4499c594-bd8b-4c8a-92cd-e731bef833d6" />

**Passo 5:** 

<img width="516" height="47" alt="ex 5" src="https://github.com/user-attachments/assets/b23f87b9-066b-4b13-a608-60cdd0420160" />

**Passo 6:** 

<img width="411" height="15" alt="ex 6" src="https://github.com/user-attachments/assets/5fa746d7-c54f-4446-b0f0-6c8ac1a9514c" />

<p>
  
  Para finalizar, vamos executar as migrações para o banco de dados. 
</p>

- O comando a seguir cria uma tabela chamada user_estudantes:
  <img width="582" height="15" alt="ex 7" src="https://github.com/user-attachments/assets/1d41658c-4618-4613-ae03-ef882867c687" />

<p>
  
  Ao executar o comando anterior, a tabela user_estudantes será criada no seguinte caminho (exercicio/database/migrations): 
</p>

<img width="284" height="111" alt="ex 10" src="https://github.com/user-attachments/assets/77a894e1-035f-442f-b444-bc93e48f7233" />

<p>
  Neste arquivo, vamos criar os campos da nossa tabela user_estudantes:
</p>

<img width="767" height="606" alt="ex 9" src="https://github.com/user-attachments/assets/82f62e0d-27b0-46df-9df4-991be68fd213" />

- Após a criação dos campos, digite o seguinte comando para publicar as alterações feitas:

   <img width="419" height="17" alt="ex 8" src="https://github.com/user-attachments/assets/fe71c9fd-5df7-4e54-ad4d-8352dc3d0fb4" />

<p>
 E pronto, agora a tabela ja está criada no phpMyAdmin:
</p>

<img width="666" height="203" alt="mysql" src="https://github.com/user-attachments/assets/3e232bee-68a8-4994-9393-275311095325" />






