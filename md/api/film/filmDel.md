## Удаление фильма

## ![DELETE](../img/delete.svg) / film/{filmId}

**_Удаляет_** фильм из системы.  
**_Возвращает_** список всех фильмов и сеансов  

**_Примечание_** при удалении фильма автоматически удаляются все сеансы связанные с этим фильмом

## Параметры:

- **filmId** - ID удаляемого фильма  (Например `34`) - указывают в url адресе

## Результат (`result`)

```javascript  
{  
  films: [], // Список фильмов
  seances: [], // Список сеансов 
}  
```