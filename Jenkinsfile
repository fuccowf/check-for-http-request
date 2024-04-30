def response = httpRequest 'http://localhost:8900'
println("Status: "+response.status)
println("Content: "+response.content)

if (response.status == '200' && response.content == '{"message":"Hello World"}') {
    echo 'Ответ был получен! Все работает!'
} else {
    error 'Что-то не работает..'
}
