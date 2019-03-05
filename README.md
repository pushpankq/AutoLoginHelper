# AutoLoginHelper

1. Add 
if  Helper.getUserDefault(key: "token") != nil {
                //Login Suucess Skip for the login screen.
                //and go to main screen.
                let dashboard = UIStoryboard(name: "Main", bundle: nil).instantiateViewController(withIdentifier: "dashboardID")
                window?.rootViewController = dashboard
            }
 in AppDelegte in didFinishLaunchingWithOptions
 
 And save the token after login
