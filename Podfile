# Uncomment the next line to define a global platform for your project
platform :ios, '9.0'
source "https://gitlab.linphone.org/BC/public/podspec.git"
source "https://github.com/CocoaPods/Specs.git"

def basic_pods
	if ENV['PODFILE_PATH'].nil?
		pod 'linphone-sdk', '~> 4.1-221-g241bbf9'
		else
		pod 'linphone-sdk', :path => ENV['PODFILE_PATH']  # loacl sdk
	end
	
	pod 'Firebase/Core'
	pod 'Fabric', '~> 1.9.0'
	pod 'Crashlytics', '~> 3.12.0'
	pod 'Firebase/Performance'
end

target 'latestCallsWidget' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for latestCallsWidget

end

target 'latestChatroomsWidget' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for latestChatroomsWidget

end

target 'liblinphoneTester' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for liblinphoneTester
  basic_pods
  
  target 'liblinphoneTesterTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'linphone' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for linphone
  basic_pods

  target 'linphoneTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

target 'linphoneExtension' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for linphoneExtension

end

target 'richNotifications' do
  # Uncomment the next line if you're using Swift or would like to use dynamic frameworks
  use_frameworks!

  # Pods for richNotifications

end
