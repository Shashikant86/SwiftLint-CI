targets_to_lint = ["SwiftLint-CI", "SwiftLint-CITests", "SwiftLint-CIUITests"]

targets_to_lint.each do |target|
  target "#{target}" do
    use_frameworks!
    pod 'SwiftLint'
  end
end
