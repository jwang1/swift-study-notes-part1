# swift-study-notes-part1
mostly based on Jonathon Manning, Paris Buttfield-Addison &amp; Tim Nugent's Learning Swift 2nd Edition covers Swift 3.x


1) implecit type

let arrs = [1, 2, 3, 4, 5]
var sum

for nbr in  arras {
  sum += nbr
}


2) idiom

for idx in 1 ... 10 {
 // note the 3 dots
}


3) swtiches

let intSw = 3

swtich intSw {
case 0: 
  print("0")
case 1: 
case 2:
case 3:
  print("no greater than 3")
default:
  print("more than 3")
}


4) tuple switch, also notice the underscore

let tupleSW = ("yes", 123)

switch tupleSW {
 case ("yes", 123):
    print("correct")
 case ("yes", _):
    print("tuple contains yes, and something else")
 case (let string, _):
    print("tuple contains the string '\(string)' and something else")
 default: 
    break
}
 
