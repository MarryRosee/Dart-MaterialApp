# Dart-MaterialApp
Dart-MaterialApp
void main() {
  MaterialApp(
    title: "instagram",
    fontSize: ThemeData(themeName: "materialtheme", themeSize: 6),
    textColor: MyHomePage(pageName: "app1", pageSize: 6),
  );
}

class MaterialApp {
  MaterialApp({String? title, ThemeData? fontSize, MyHomePage? textColor}) {}
}

class ThemeData {
  ThemeData({String? themeName, int? themeSize}) {
    print("themedata");
  }
}

class MyHomePage {
  MyHomePage({String? pageName, int? pageSize}) {
    print("pagedata");
  }
}
