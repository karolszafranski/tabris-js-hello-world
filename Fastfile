platform :ios do
  desc "Build the Tabris.js Hello World App"
  lane :buildDebug do
    match(type: "development", git_url: "https://github.com/eclipsesource/match-certificates")
    # tabris build...
    sh "cd .. && tabris build ios --device --debug"
  end
  desc "Deploy App to the Appstore"
  lane :deploy do
    #appstore(ipa: ENV['CORDOVA_IOS_RELEASE_BUILD_PATH'])
  end
end
