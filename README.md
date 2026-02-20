# README - FitTrack (Nome Temporário)

## 🏋️‍♂️ FitTrack - Seu Diário de Treino Inteligente

FitTrack é um aplicativo mobile desenvolvido para ajudar pessoas a organizarem seus treinos de academia, acompanharem sua evolução e manterem a consistência nos exercícios. Com foco em simplicidade e funcionalidades essenciais, o app permite que o usuário se preocupe apenas em treinar enquanto o FitTrack cuida do registro e acompanhamento.

## 📱 Sobre o Projeto

Este aplicativo nasceu da necessidade de ter uma ferramenta simples, mas completa, para registro de treinos de academia. Diferente de apps complexos ou redes sociais fitness, o FitTrack foca no essencial: ajudar você a evoluir nos seus treinos com dados claros e interface intuitiva.

## ✨ Funcionalidades

### 🎯 Core (Essencial)
- **Montagem de Treino Personalizado** - Crie e organize seus treinos por dia da semana
- **Registro de Cargas e Repetições** - Acompanhe seu desempenho treino a treino
- **Timer de Descanso** - Cronômetro automático entre séries
- **Calendário de Treinos** - Marque seus dias de treino e visualize seu histórico

### 📊 Acompanhamento
- **Gráficos de Progresso** - Visualize sua evolução nos principais exercícios
- **Fotos de Progresso** - Linha do tempo com suas fotos para comparação visual
- **Registro de Medidas** - Acompanhe peso, medidas corporais e % de gordura
- **Recordes Pessoais** - Destaque automático quando você supera suas marcas

### 🎓 Educacional
- **Biblioteca de Exercícios** - Mais de 200 exercícios com vídeos/GIFs demonstrativos
- **Instruções Detalhadas** - Descrição passo a passo e músculos trabalhados
- **Modo Offline** - Acesse seus treinos e vídeos sem internet

### ⚙️ Experiência do Usuário
- **Modo Escuro** - Interface confortável para qualquer horário
- **Integração com Saúde** - Sincronia com Apple Health, Google Fit e Samsung Health
- **Notificações Inteligentes** - Lembretes de treino e alarmes de descanso
- **Design Rápido** - Interface otimizada para uso durante o treino

### 🚀 Diferenciais
- **Modo Academia/Casa** - Filtre exercícios por equipamento necessário
- **Controle por Smartwatch** - Integração com wearables
- **Modo Descanso Ativo** - Sugestões de alongamento durante as pausas
- **Exportação de Dados** - Compartilhe ou faça backup do seu histórico

## 🛠️ Tecnologias Utilizadas

- **Frontend:** React Native / Expo
- **Backend:** Node.js com Express
- **Banco de Dados:** PostgreSQL (dados do usuário) + Redis (cache)
- **Armazenamento:** AWS S3 (vídeos e imagens)
- **Autenticação:** JWT + OAuth2 (Google, Apple)
- **Push Notifications:** Firebase Cloud Messaging / APNS

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/fittrack.git

# Entre no diretório
cd fittrack

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Inicie o projeto
npm run start
```

## 🎯 Roadmap

### Versão 1.0 (MVP)
- [x] Cadastro de treinos personalizados
- [x] Timer de descanso básico
- [x] Registro de cargas e repetições
- [x] Calendário de treinos

### Versão 1.5
- [ ] Biblioteca de exercícios com imagens
- [ ] Gráficos de progresso básicos
- [ ] Modo escuro
- [ ] Backup na nuvem

### Versão 2.0
- [ ] Vídeos demonstrativos
- [ ] Integração com wearables
- [ ] Compartilhamento social
- [ ] Planos de treino prontos

### Versão 2.5
- [ ] IA para sugerir ajustes de carga
- [ ] Comunidade e desafios
- [ ] Modo treino em casa
- [ ] Personal trainers podem criar contas para alunos

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

- **Desenvolvedor:** Alvaro Scorza
- **Email:** alvscorza@gmail.com

## 🙏 Agradecimentos

- Comunidade React Native
- Todos os beta testers que contribuíram com feedback

---

**FitTrack** - Transformando seus treinos em dados, e dados em evolução. 💪
