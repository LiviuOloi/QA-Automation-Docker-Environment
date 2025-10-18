<img width="1915" height="617" alt="Image" src="https://github.com/user-attachments/assets/42b91e92-6c4e-4787-b23c-034f1c10e50a" />

<img width="1914" height="673" alt="Image" src="https://github.com/user-attachments/assets/efa0a1d2-2fc0-4319-91e7-70becb9e3282" />

Ruland comanda docker compose down -v am observat faptul ca volumele din containerul respectiv se sterg, deci nu mai persistam datele din DB.

Acest lucru fiind important pentru a ne asigura ca nu lucram cu date vechi si ca la urmatoarea rulare baza de date e goala.

Am observat asta ruland din nou comanda docker compose up -d si am vazut ca trebuie sa refac tabelul.