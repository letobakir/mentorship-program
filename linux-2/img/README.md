# Instalacija Ubuntu-a kao Windows Subsystem for Linux (WSL)

Ovaj vodič opisuje korake za instalaciju i podešavanje Ubuntu-a u okviru Windows Subsystem for Linux (WSL).

## 1. Omogućavanje WSL funkcionalnosti

1. Otvori **PowerShell** kao administrator (desni klik na Start dugme > **Windows Terminal (Admin)** ili **PowerShell (Admin)**).
2. Unesi sledeću komandu i pritisni **Enter**:

   ```powershell
   wsl --install
   ```

3. Sačekaj da se instalacija završi i restartuj računar ako se to zatraži.

Ako WSL nije dostupan kroz `wsl --install`, možeš ga ručno omogućiti:

1. Otvori **Control Panel** > **Programs** > **Turn Windows features on or off**.
2. Označi sledeće opcije:
   - **Windows Subsystem for Linux**
   - **Virtual Machine Platform**
3. Klikni **OK** i restartuj računar.

## 2. Instalacija Ubuntu-a

1. Otvori **Microsoft Store**.
2. Pretraži **Ubuntu**.
3. Izaberi verziju (preporučuje se **Ubuntu 22.04 LTS**).
4. Klikni **Get** (ili **Install**) i sačekaj da se instalacija završi.

## 3. Pokretanje i početno podešavanje

1. Otvori **PowerShell** ili **Command Prompt** i unesi:

   ```powershell
   wsl
   ```

   ili

   ```powershell
   ubuntu
   ```

2. Sačekaj da se Ubuntu pokrene prvi put.
3. Kada se zatraži, unesi korisničko ime i lozinku.
4. Ubuntu je sada instaliran i spreman za korišćenje.

