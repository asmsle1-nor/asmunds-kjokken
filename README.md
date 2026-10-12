# Åsmunds Kjøkken – Expo-prototype 0.1

Dette er kildekoden til en tidlig React Native/Expo-prototype. Ingen kontoer eller skydata er koblet til. Lokale data lagres med AsyncStorage på enheten. Eksempeloppskrifter er ikke kvalitetssikrede produksjonsoppskrifter.

## Kjøring
1. Installer Node.js (på en PC eller skyutviklingsmiljø).
2. I prosjektmappen: `npm install`
3. Start: `npx expo start`
4. Bruk Expo Go på iPhone for å åpne QR-koden. Expo Go er til utvikling, ikke en ferdig distribusjonsløsning. Versjoner av Expo Go og Expo SDK må være kompatible.
5. For nettlesertesting: `npm run web`.

## Neste utviklingstrinn
Supabase-innlogging, Row Level Security og separat lagring per bruker; fast Åsmund-bibliotek; redigering; mengdebasert ingrediensmatching; ekte varsler; import av verifiserte oppskrifter; sikkerhetskopi.

## Merk
Ingen ZIP-fil er en installerbar iOS-app. Prosjektet er ikke bygget eller testet på en fysisk iPhone i denne leveransen.
