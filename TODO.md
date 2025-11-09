# TODO: Change UI to Step Counter

- [x] Update lib/main.dart: Change app title to "Step Counter", update home screen buttons to "Add Step", "View Steps", "Edit Step".
- [x] Update lib/models/word.dart: Rename MovieBooking to StepData, add fields (steps, date), update factory and toMap.
- [x] Update lib/models/user.dart: Keep as is.
- [x] Update lib/services/firestore_service.dart: Change collection to 'steps', update methods (addStep, getSteps, searchSteps, updateStep).
- [x] Update lib/screens/login_screen.dart: Change title to "Step Counter Login".
- [x] Update lib/screens/book_appointment_screen.dart: Change to Add Step screen with form for steps, date.
- [x] Update lib/screens/search_screen.dart: Change to View Steps screen, display step history.
- [x] Update lib/screens/edit_appointment_screen.dart: Change to Edit Step screen, modify steps.
- [x] Update test/widget_test.dart to match new UI.
- [x] Followup: Run flutter pub get, test the app.
