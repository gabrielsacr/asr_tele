# Avaliação 5 – *Proxy* reverso
1. Instalar o NGINX e configurar um *proxy* reverso como apresentado nos tutoriais.

![1](https://github.com/gabrielsacr/asr_tele/assets/114113950/dad3be0c-8160-4ddc-aea5-fe594d00defe)

***Figura 1**. Endereço não é localizado quando o NGINX está inativo.*

---

![2](https://github.com/gabrielsacr/asr_tele/assets/114113950/831c1255-481a-4bfc-9ad2-6c9686e528a3)

***Figura 2**. Configuração para o NGINX funcionar como *proxy* reverso, redirecionando do endereço `localhost:8080/dashboard` para `localhost/dashboard`.*

---

![3](https://github.com/gabrielsacr/asr_tele/assets/114113950/e1c0eca4-595d-4942-beb6-c88aa34f07a1)

***Figura 3**. Com o NGINX ativo e configurado como *proxy* reverso, o endereço `localhost/dashboard` redireciona para `localhost:8080/dashboard`.*
