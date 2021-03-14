# RTL Flutter

Hi, This basic RTL Flutter Application


## Step 1 
### pubspec.yaml 

dependencies:
`flutter_localizations:
-------sdk: flutter`

Then **save** file & **Run** `flutter pub get`

## Step 2

In main.dart file
under **MaterialApp** add this code
      `localizationsDelegates: [
          GlobalMaterialLocalizations.delegate,
          GlobalWidgetsLocalizations.delegate,
      ],
      supportedLocales: [
      - -Locale("ar", "SA"), 
      ],`

## Test 
Just download
Then run `flutter run`
