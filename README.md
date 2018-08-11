# Dicee

### Simple Dice random generate application

```swift
class ViewController: UIViewController {
    
    var randomDiceIndex1: Int = 0
    var randomDiceIndex2: Int = 0
    
    let diceArray = [
        "dice1",
        "dice2",
        "dice3",
        "dice4",
        "dice5",
        "dice6"
    ]

    @IBOutlet weak var diceImageView1: UIImageView!
    @IBOutlet weak var diceImageView2: UIImageView!
    
    override func viewDidLoad() {
        super.viewDidLoad()
        
        updateDiceImages()
        
    }
   ```
   
