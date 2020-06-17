# Helpers
Just some helpers that I really need sometimes.

## Common used code

### Common ViewController

```Swift
// MARK: - UI
let <#T##view#> = <#T##UIView()#>

// MARK: - Lifecycle
override func viewDidLoad() {
  super.viewDidLoad()
  setup()
}

// MARK: - Setup
func setup() {
  setup<#T##functionName#>()
  layout()
}

private func setup<#T##functionName#>() {
  <#T##view#>.addSubview(<#T##view#>)
}

// MARK: - Layout
private func layout() {
  
  <#T##view#>.translatesAutoresizingMaskIntoConstraints = false
  
  NSLayoutConstraint.activate([
  
  ])
}
```
