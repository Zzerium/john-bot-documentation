---
description: >-
  Liste des variables disponibles à utiliser dans la configuration du système de
  tickets, du messages d'arrivée et du messages de départ
---

# Variables

{% hint style="info" %}
Attention ! Ces variables sont seulement utilisables pour la configuration du système de tickets, du système de messages d'arrivée et du système de messages de départ.
{% endhint %}

| Variable               | Description                                                                      | Exemple                                                                                     |
| ---------------------- | -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| {user}                 | Affiche le nom et le tag de l'utilisateur.                                       | Utilisateur#0001                                                                            |
| {user.name}            | Affiche le nom de l'utilisateur.                                                 | Utilisateur                                                                                 |
| {user.mention}         | Affiche la mention de l'utilisateur.                                             | @Utilisateur                                                                                |
| {user.id}              | Affiche l'identifiant de l'utilisateur.                                          | 012345678912345678                                                                          |
| {user.avatar\_url}     | Affiche le lien de l'avatar de l'utilisateur.                                    | https://cdn.discordapp.com/avatars/958547309728256081/c83207e3ef95fb6c9198562d0d04714f.webp |
| {server.name}          | Affiche le nom du serveur.                                                       | John-Bot                                                                                    |
| {server.id}            | Affiche l'identifiant du serveur.                                                | 012345678912345678                                                                          |
| {server.icon\_url}     | Affiche l'icône du serveur.                                                      | https://cdn.discordapp.com/icons/959269961572962314/01f8699526e02fd34266e07835bd1de5.webp   |
| {server.member\_count} | Affiche le nombre de membres que compte le serveur.                              | 10                                                                                          |
| {ticket\_number}       | Affiche le nombre de tickets ouvert sur le panneaux après l'ouverture du ticket. | 5                                                                                           |
