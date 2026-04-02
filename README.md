# Frontend Angular - Tela de Login

Este projeto é um frontend desenvolvido em **Angular** com foco inicial em uma **tela de login**, integrada a um backend em **Python Django** para autenticação de usuários.

## Objetivo

Criar uma interface moderna e organizada para autenticação, permitindo que o usuário informe suas credenciais e se conecte ao backend Django por meio de uma API.

## Tecnologias utilizadas

- **Angular**
- **TypeScript**
- **HTML5**
- **CSS3 / SCSS**
- **Angular Router**
- **Angular Forms / Reactive Forms**
- **HTTP Client**
- **Backend:** Python + Django + Django REST Framework

## Funcionalidades iniciais

- Tela de login
- Validação de campos
- Integração com API Django
- Tratamento de erro de autenticação
- Armazenamento de token
- Redirecionamento após login
- Proteção de rotas autenticadas

## Estrutura esperada do projeto

```bash
src/
 ├── app/
 │   ├── core/
 │   │   ├── services/
 │   │   │   └── auth.service.ts
 │   │   ├── guards/
 │   │   │   └── auth.guard.ts
 │   │   └── interceptors/
 │   │       └── auth.interceptor.ts
 │   ├── features/
 │   │   └── auth/
 │   │       ├── login/
 │   │       │   ├── login.component.ts
 │   │       │   ├── login.component.html
 │   │       │   └── login.component.scss
 │   ├── shared/
 │   ├── app-routing.module.ts
 │   ├── app.component.ts
 │   └── app.module.ts
 ├── environments/
 │   ├── environment.ts
 │   └── environment.prod.ts
 └── ...