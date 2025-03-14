# 🚀 Configuração do Projeto

## 📦 Instalação

1. Configure o seu package:
   ```sh
   npm init
   ```
2. Instale as dependências:
   ```sh
   npm install
   ```
3. Atualize o arquivo `.env` com as configurações adequadas.

4. Remova os arquivos `.gitkeep`, se necessário.

---

## 📂 Estrutura de Arquivos

- `swagger.json` - Arquivo para documentação das rotas da API.
- `ecosystem.config.json` - Arquivo de configuração para deploy, utilizado com PM2.

---

## 🚀 Executando no Servidor

Para iniciar a aplicação com PM2:
```sh
pm install -g pm2
npx tsc
pm2 start ecosystem.config.json
```