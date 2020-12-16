source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '9.0'
inhibit_all_warnings!
use_frameworks!
install! 'cocoapods', :deterministic_uuids => false

def shared_pods
    pod 'Alamofire',                    '~> 4.3.0'
    pod 'RealmS',                       '~> 2.2.0'
    pod 'SwiftLint',                    '~> 0.16.1'
end

def app_pods
    # UI
    pod 'SVProgressHUD',                '~> 2.1.2'
    pod 'PureLayout',                   '~> 3.0.2'
    pod 'IQKeyboardManagerSwift',       '~> 4.0.8'
    pod 'LGSideMenuController',         '~> 2.0.5'
    pod 'Charts',                       '~> 3.0.1'
    pod 'FSCalendar',                   '~> 2.7.4'
    pod 'Kingfisher',                   '~> 3.7'

    # Security
    pod 'SAMKeychain',                  '~> 1.5.1'

    # Utils
    pod 'SwiftUtils',                   '~> 2.1.1'
    pod 'SwiftDate',                    '~> 4.0'
    pod 'XCGLogger',                    '~> 4.0'
    pod 'SwiftyJSON',                   '~> 3.1.4'
    
    # HTML
    pod 'MWFeedParser/NSString+HTML',   '~> 1.0.1'
end

def test_pods
end

target 'FoodAndFitness' do
    app_pods
    shared_pods

target 'FoodAndFitnessTests' do
    inherit! :search_paths
end
end
