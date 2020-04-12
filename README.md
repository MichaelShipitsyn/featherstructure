
<div align="center">
  <img src="./assets/feather.svg" alt="feather" height="130" />
</div>

# Feather Structure

## Схема 

├── api  
├── features   
├── configs   
├── constants   
├── layout    
├── libs   
├── pages            
├── shared    
├── services   
├── static    
├── src   
├── theme      
├── webpack    

## Описание

* `api`  
Директория с функциями делающие ajax-запросы.  
Организовать эти функции можно по `endpoint` вашего `rest api`  
Например:  
```
├── api  
    ├── profile // /api/v1/profile
        ├── index.js // В index.js можно записать все функции взаимодействующие с endpoint.
                     // Либо создавать под каждую функцию отдельный файл.
                     
```
```js
// index.js

export function getUserInfo() {}

export function saveUserInfo() {}
```
