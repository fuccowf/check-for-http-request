def response = httpRequest 'http://localhost:8900'

println(response.status)
println("Content: "+response.content)

if (response.status == '200') {
    echo 'Ответ был получен! Все работает!'
}else {
    error 'Ответ не получен!'
}
