# A1 LATIHAN KOTLIN
Michael Agustinus - c14180145

## Soal 1
```python
fun main() {
    
    var n = 3
    val m = 2
    var s = 'A'
    var count = 1
    val template = "n: $n , m: $m , s:$s"
    var total = m * 2 + 2
    
    for(i in 1 until total){
      for(j in 1 until total) {
        if( j == n){
          print("*")
          s = s + m
        }else{
          if(j == 5){
            print(s)
          }else{
            print(s)
            s = s + m
          }
        }
        count++
        if(count == 7){
          s = 'A'
          count = 1
        }
      }
      
      if(n == total){
        n = 1
      }
      n++
      print("\n")
    }
    
  
}
```

## Soal 2

```
fun main() {
    val text = readLine()
    
    val count = text.toString().trim()
    val counted = count.split(" ").size
    println("jumlah kata: $counted")
}
```