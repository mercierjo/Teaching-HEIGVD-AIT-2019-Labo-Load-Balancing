# Lab 03 - Load Balancing
Authors: Mercier Jordan, Vogel Maximilian

Date: 13.11.2019

## Task 1: Install the tools

### 1
A chaque refresh de la page, les paramètres qui changent sont: le serveur web vers lequel on est redirigé par le load balancer change à chaque requête de celui en 192.168.42.11 (s1) à 192.168.42.22 (s2) ainsi que la session id. On change donc à chaque requête d'un serveur à l'autre et à chaque fois une nouvelle session est ouverte. Le compteur sessionsViews reste donc toujours à 1, puisque chaque session ne fait qu'une vue.

### 2

Pour l'instant à chaque requête on accède à l'application en tant qu'utilisateur différent: ce n'est pas du tout ce qu'on veut. Etant donné qu'on accède toujours depuis le même client, on aimerait que notre session reste toujours la même en suivant ce mode d'opération.

De manière générale, on voudrait 1 session par client user et que cet id soit le même, peu importe lequel de nos deux serveurs est accédé.

### 3

### 4

### 5

## Task 2: Sticky sessions



## Task 3: Drain mode

## Task 4: Round robin in degraded mode

## Task 5: Balancing strategies
