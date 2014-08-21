screencrak
==========
#import "iOS-Screenshot-Automator/Helper.js"


test("Login Test", loginTest);
test("Route Test", routeDetailsTest);
...

function loginTest(target, app)
{
    var window = app.mainWindow();
    var navBar = window.navigationBar();

    ...

    captureLocalizedScreenshot("Login");

    ....
}
