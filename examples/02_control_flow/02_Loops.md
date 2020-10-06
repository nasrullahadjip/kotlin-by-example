
fun findPrimes(start : Int, stop : Int) {
    for(i in start..stop) {
        if(isPrime(i)) println("$i is Prime")
    }
}
 
 
fun main() {
    findPrimes(30,50)
}
