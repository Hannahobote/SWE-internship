# Requirement specification

for example

## 1. Beställnings sida (Order)
- Cupcake, tårta och cheesecake bör ha sina egna beställnings formulär.
- Det bör finnas ett gemensamt formulär för personlig information för att veta vem som har beställt en produkt.
- Kunden bör få en länk till sin beställning för att se hur långt den har kommit. Denna länken ska skickas till kundens email
- Kunden bör spara länken till sin individuella beställning.
- Kunden bör INTE kunna utföra CRUD-operationer på en beställning som redan är skickad.
- Kunden bör inte ha tillgång till beställningar gjorda av andra kunder.
- Kunden bör endast kunna kommunicera med ägaren genom denna länk.
- Kunden bör endast kunna beställa en produkt två veckor från dagens datum. Leveransdatumet bör vara 14 dagar framåt, så att ägaren har tid att baka produkten.

## 2 Login (Auth)
1. Logga in på administratörsportalen
2. Ägaren bör kunna logga in på applikationen med angivna användarnamn och lösenord
3. En kund ska inte ha tillgång till routes som endast är behöriga till administratören
## 3 Admin sida
- Endast ägaren bör ha tillgång till adminsidan när hen är inloggad.
- Ägaren bör kunna se alla sina beställningar på adminpanelen. Informationen bör vara följande:
- En länk till den individuella beställningen.
