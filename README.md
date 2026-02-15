

# Retrofit
Retrofit hoitaa HTTP-pyyntöjen hallinnan ja muuntaa JSON-vastaukset suoraan Kotlin-dataluokiksi. Taustalla Gson vastaa JSONin muunnoksesta dataluokiksi.

# Coroutines
API-kutsut suoritetaan taustasäikeessä coroutinesin avulla. UI päivittyy automaattisesti, kun data on ladattu.

# UI-tila
ViewModel hallitsee WeatherUiState-oliota. Jetpack Compose reagoi tilamuutoksiin automaattisesti, mikä pitää käyttöliittymän ajan tasalla.

# API-avain
API-avain on tallennettu local.properties-tiedostoon, josta se siirtyy BuildConfigiin ja edelleen Retrofitin käyttöön.
