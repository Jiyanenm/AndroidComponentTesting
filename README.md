# Login App (Android - Jetpack Compose)

A minimal, fully tested login screen with:

- MVVM architecture
- Jetpack Compose UI
- Input validation
- Lockout after 3 failed attempts
- Offline handling
- Remember Me (token persistence)
- UI + Unit tests
- No external dependencies

## Project Structure

app/
├─ ui/LoginScreen.kt
├─ viewmodel/LoginViewModel.kt
├─ model/LoginUiState.kt
├─ repository/AuthRepository.kt
├─ androidTest/LoginScreenTest.kt
├─ test/LoginViewModelTest.kt


## Features

✔ Email/password validation  
✔ Button enable/disable  
✔ Error messaging  
✔ Offline mode  
✔ Lockout after 3 failures  
✔ Remember me  
✔ Deterministic tests

## Run Tests

