platform :ios, '8.0'
use_frameworks!

def shared_pods
    pod 'Mapbox-iOS-SDK', :podspec => 'https://raw.githubusercontent.com/mapbox/mapbox-gl-native/ios-v3.4.0-beta.3/platform/ios/Mapbox-iOS-SDK-symbols.podspec'
    pod 'MapboxDirections.swift', :git => 'https://github.com/mapbox/MapboxDirections.swift.git', :commit => 'ceaf58b780fc17ea44a9150041b602d017c1e567'
end

target 'MapboxNavigation' do
    shared_pods
end

target 'MapboxNavigationTests' do
    shared_pods
end

target 'Example' do
    shared_pods
end