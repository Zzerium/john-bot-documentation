---
description: >-
  Liste des variables disponibles à utiliser dans la configuration du système de
  tickets, du messages d'arrivée et du messages de départ
---

# Variables

{% hint style="info" %}
Attention ! Ces variables sont seulement utilisables pour la configuration des messages d'arrivée, de départ et la configuration des messages du système de ticket.
{% endhint %}

| Liste des variables | Description des variables                                                                           |
| ------------------- | --------------------------------------------------------------------------------------------------- |
| {user}              | Affiche le nom et le tag de l'utilisateur (Utilisateur#0001).                                       |
| {user.name}         | Affiche le nom de l'utilisateur (Utilisateur).                                                      |
| {user.mention}      | Affiche la mention de l'utilisateur (@Utilisateur).                                                 |
| {user.id}           | Affiche l'identifiant de l'utilisateur (123456789012345678).                                        |
| {server.name}       | Affiche le nom du serveur sur lequel l'utilisateur fait son arrivée, son départ ou ouvre un ticket. |
| {membercount}       | Affiche le nombre de membres que compte le serveur après l'arrivée ou le départ de l'utilisateur.   |
| {ticketnumber}      | Affiche le nombre de tickets ouvert sur le panneaux après l'ouverture du ticket.                    |
