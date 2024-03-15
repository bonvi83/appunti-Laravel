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

## Creazione di un nuovo progetto da template

1. scarica la repo ed aprila in VS Code, oppure clona direttamente la repo template

2. apri un terminale ed installa Composer (per il back end)

```
composer install
```

3. per far partire il server lato back end

```
php artisan serve
```

4. apri un nuovo terminale ed installa node modules (per il front end)

```
npm install
```

5. avvia il server lato front end

```
npm run dev
```

6. copia il file `.env.example` e rinominalo `.env` nella stessa posizione

7. apri un altro terminale e crea una APP KEY (oppure sulla pagine di errore clicca su generate key)

```
php artisan key:generate
```

8. importa tutti i file che ti servono nelle relative cartelle e...

### CHE DIO CE LA MANDI BUONA!
