# 📄 Estudo de Caso — Spotify

Proposta: Implementar um modelo de Machine Learning para prever se um usuário do Spotify irá cancelar a assinatura ou permanecer ativo.

### Informações Gerais
**** Cada linha representa um usuário exclusivo do Spotify.

user_id → Unique identifier for each user

gender → User gender (Male/Female/Other)

age → User age

country → User location

subscription_type → Type of Spotify subscription (Free, Premium, Family, Student)

listening_time → Minutes spent listening per day

songs_played_per_day → Number of songs played daily

skip_rate → Percentage of songs skipped

device_type → Device used (Mobile, Desktop, Web)

ads_listened_per_week → Number of ads heard per week

offline_listening → Offline mode usage

is_churned → Target variable (0 = Active, 1 = Churned)

Dataset Type: Mixed (numeric + categorical)

### Perfil básico -  Responda os questionamentos abaixo
* Qual é quantidade de usuário por sexo?
* Qual é a média em minutos que os usuários ouvem por dia?
* Qual é a quantidade de usuários por pais?
* Qual é a distribuição de usuários (sexo) por pais?
* Qual é a média de múscias que são "puladas!" pelos usuários?
* Qual é a média de músicas tocadas por dia?
* Qual tipo de device é mais utilizado?
* Qual é a distribuição do tipo de assinatura por sexo e pais?
* Qual é a média de idade no geral entre os usuários?
* Qual é a média de idade por sexo?
* Qual é a relalização entre a variável *age* e *device_type*?
* Apresente as características do dataset.
* Existem valores ausentes?
* Apresente a matrix de correlação entre as variáveis do dataset.

### Métricas de avaliação dos modelos
- Acuracia (Accuracy)
- Precisão (Precision)
- Recall
- F1 - Score