# PlentoApi

# Base URL : https://plento-api.herokuapp.com




# Requêtes

## POST /login

### Retourne un compte à partir de ses informations de connexion

| Paramètre | Type | Description |
| --------- | ---- | ----------- |
| email | String | Adresse email du compte |
| password | String | Mot de passe du compte |

## POST /signup

### Crée un compte et le retourne

| Paramètre | Type | Description |
| --------- | ---- | ----------- |
| email | String | Adresse email du compte |
| password | String | Mot de passe du compte |
| pseudo | String | Pseudo du compte |




# Types

## Compte

| Paramètre | Type | Description |
| --------- | ---- | ----------- |
| _id | String | Identifiant du compte |
| email | String | Adresse email du compte |
| password | String | Mot de passe du compte |
| pseudo | String | Pseudo du compte |
| token | String | Token du compte |
