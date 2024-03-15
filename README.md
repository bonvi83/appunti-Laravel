# Laravel

## Creazione di un nuovo progetto

1. Crea una nuova cartella con il nome del progetto
2. Apri la cartella in VSCode
3. Apri un terminale da VSCode ed esegui il comando per installare (in questo caso l'ultima versione della 9)

```
composer create-project laravel/laravel:^9.x .
```

4. Avviamo l'artisan

```
php artisan serve
```

Se non funziona:

```
php -S localhost:8000 -t public
```

5. Entra nella cartella `resource`, `views` e cancella il file `welcome.blade.php`

6. Crea una file `.blade.php`

7. Entra nella cartella `routes`, apri il file `web.php` e cambia il nome del file cancellato, con quello che hai creato nella riga

```
Route::get('/', function () {
   return view('nome del file che hai creato')
});
```

### CHE DIO CE LA MANDI BUONA!
