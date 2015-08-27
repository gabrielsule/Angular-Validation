# Angular-Validation
Uso de la librería angular-messages.min.js para validar sencillamente formularios

pueden utilizar el CDN de Angular para la utilización de las librerías

https://code.angularjs.org/1.4.4/angular.min.js

https://code.angularjs.org/1.4.4/angular-messages.min.js

En los elempentos input utilizar el id para que angular lo reconzca, e invocando al atributo deseado con ng-message mostramos el error

```
<input type="text" id="txtNombre" name="txtNombre" ng-model="nombre" class="form-control" placeholder="ej.: Etelvina" required />
<div ng-messages="registro.txtNombre.$error">
  <div ng-message="required">
    el campo es requerido <span class="glyphicon glyphicon-exclamation-sign" aria-hidden="true"></span> 
  </div>
</div> 
```
