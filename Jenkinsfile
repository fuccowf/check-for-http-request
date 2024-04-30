def response = httpRequest 'http://localhost:8900'

println("Response: " + response.status)
println("Content: " + response.content)

if (response.status == 200) {
    println("Ответ был получен! Все работает!")
}
else {
   error 'Ответ не получен!'
}
