# AXIOS
## Setup
`import axios from 'axios';`

**Para enviar cualquier petición utilizando axios primero debemos importar axios del paquete axios.**
## GET
**Sintaxis.**
```
import axios from 'axios';
...
const response = await axios.get(<endpoint>);
```
**Puede utilizar el método get disponible en él para enviar la solicitud GET al endpoint proporcionado como argumento.**
**Sintaxis con parámetros.**
```
import axios from 'axios';
...
const response = await axios.get(<endpoint>, {
	paramsOne: paramOneValue,
	paramsTwo: paramTwoValue,
	paramsThree: paramThreeValue
});
```
**Si tu petición depende de algunos parámetros de consulta, puedes simplemente pasarlos como un objeto como segundo argumento al método get.**
**Axios se encargará del resto por ti.**
## POST
**Sintaxis.**
```
import axios from 'axios';
...
const response = await axios.post(<endpoint>, {
	id: userID,
	userAge: 22,
	userName: ‘Mike’
});
```
**Puede utilizar el método post disponible en él para enviar la solicitud POST al endpoint proporcionado  como argumento. El segundo argumento se adjuntará como carga útil a la solicitud.**
## PUT
**Sintaxis.**
```
import axios from 'axios';
...
const response = await axios.post(<endpoint>, {
	id: userID,
	userAge: 22,
	userName: ‘Mike’
});
```
**Puede utilizar el método put disponible en él para enviar la solicitud PUT al endpoint proporcionado como argumento. El segundo argumento se adjuntará como carga útil a la solicitud.**
## DELETE
**Sintaxis.**
```
import axios from 'axios';
...
const response = await axios.delete(<endpoint>);
```
**Puede utilizar el método delete disponible en él para enviar la solicitud DELETE al endpoint proporcionado como argumento.**