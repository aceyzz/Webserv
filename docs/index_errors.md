## 200 Status Codes

| Code | Description |
|------|-------------|
| 200 OK | La requête a été traitée avec succès. |
| 201 Created | La requête a été traitée avec succès et une nouvelle ressource a été créée. |
| 202 Accepted | La requête a été acceptée pour traitement, mais le traitement n'est pas encore terminé. |
| 203 Non-Authoritative Information | La réponse est une copie de la ressource d'origine, mais elle peut provenir d'un serveur différent. |
| 204 No Content | La requête a été traitée avec succès, mais la réponse ne contient pas de contenu. |
| 205 Reset Content | La requête a été traitée avec succès, mais l'agent utilisateur doit réinitialiser la vue. |
| 206 Partial Content | La réponse contient seulement une partie de la ressource demandée. |

## 300 Status Codes

| Code | Description |
|------|-------------|
| 300 Multiple Choices | La requête a plusieurs options possibles. |
| 301 Moved Permanently | La ressource demandée a été déplacée de façon permanente vers une nouvelle URL. |
| 302 Found | La ressource demandée a été trouvée, mais elle a été temporairement déplacée vers une autre URL. |
| 303 See Other | La réponse à la requête peut être trouvée sous une autre URL. |
| 304 Not Modified | La ressource n'a pas été modifiée depuis la dernière requête. |
| 305 Use Proxy | La requête doit être redirigée via un serveur proxy. |
| 307 Temporary Redirect | La ressource demandée a été temporairement déplacée vers une autre URL. |
| 308 Permanent Redirect | La ressource demandée a été déplacée de façon permanente vers une nouvelle URL. |

## 400 Status Codes

| Code | Description |
|------|-------------|
| 400 Bad Request | La requête est incorrecte ou mal formée. |
| 401 Unauthorized | L'accès à la ressource est refusé en raison d'une authentification manquante ou invalide. |
| 403 Forbidden | L'accès à la ressource est refusé pour des raisons de permissions. |
| 404 Not Found | La ressource demandée n'a pas été trouvée sur le serveur. |
| 405 Method Not Allowed | La méthode de requête utilisée n'est pas autorisée pour la ressource demandée. |
| 406 Not Acceptable | La ressource demandée n'est pas disponible dans un format qui respecte les en-têtes `Accept` de la requête. |
| 407 Proxy Authentication Required | L'accès à la ressource est refusé en raison d'une authentification proxy manquante ou invalide. |
| 408 Request Timeout | Le serveur a expiré le délai d'attente pour la requête. |
| 409 Conflict | La requête ne peut pas être traitée en raison d'un conflit avec l'état actuel de la ressource. |
| 410 Gone | La ressource demandée n'est plus disponible et aucune redirection n'est connue. |
| 411 Length Required | La longueur de la requête n'a pas été spécifiée. |
| 412 Precondition Failed | Une ou plusieurs conditions préalables de la requête ont échoué. |
| 413 Payload Too Large | La taille de la requête dépasse la limite autorisée par le serveur. |
| 414 URI Too Long | L'URI de la requête est trop long pour être traité par le serveur. |
| 415 Unsupported Media Type | Le type de média de la requête n'est pas supporté par le serveur. |
| 416 Range Not Satisfiable | L'intervalle de la requête ne peut pas être satisfait par le serveur. |
| 417 Expectation Failed | L'attente de la requête n'a pas été satisfaite par le serveur. |

## 500 Status Codes

| Code | Description |
|------|-------------|
| 500 Internal Server Error | Une erreur interne du serveur s'est produite. |
| 501 Not Implemented | La fonctionnalité demandée n'est pas prise en charge par le serveur. |
| 502 Bad Gateway | Le serveur agissant en tant que passerelle a reçu une réponse invalide. |
| 503 Service Unavailable | Le serveur n'est pas disponible pour le moment. |
| 504 Gateway Timeout | Le serveur agissant en tant que passerelle n'a pas reçu de réponse à temps. |
| 505 HTTP Version Not Supported | La version HTTP utilisée dans la requête n'est pas supportée par le serveur. |
| 508 Loop Detected | La requête ne peut pas être traitée car elle provoque une boucle infinie. |
| 511 Network Authentication Required | L'accès à la ressource est refusé en raison d'une authentification réseau manquante. |