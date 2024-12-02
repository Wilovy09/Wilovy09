[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=F7F7F7&width=435&lines=Wilovy%2C+self+taught+developer.;Rust+enjoyer.)](https://git.io/typing-svg)

<img src="./assets/images/b3.png" alt="banner" align="right" width="440px">
<br>
<h3 align=center>Technologies</h3>
<p align=center>
<a href="https://www.freecodecamp.org/certification/Wilovy09/scientific-computing-with-python-v7" target="_blank">
<img width="48" height="48" src="https://img.icons8.com/color/48/python--v1.png" alt="python--v1"/>
</a>
<img width="42" src="https://img.icons8.com/ios-filled/384/498fe1/typescript.png" alt="javascript"/>
<img width="48" height="48" src="https://img.icons8.com/?size=100&id=U41Than0pWOW&format=png&color=EF4823" alt="external-rust-is-a-multi-paradigm-system-programming-language-logo-color-tal-revivo"/>
<img width="48" height="48" src="https://img.icons8.com/color/48/vue-js.png" alt="vue-js"/>
<!--<img width="42" src="https://img.icons8.com/?size=100&id=44442&format=png&color=000000" alt="go"/>-->
</p>
<br/>

```rust
use actix_web::{web, get, App, HttpServer, 
Responder, HttpResponse};

#[get("/")]
async fn hello_world() -> HttpResponse {
    HttpResponse::Ok().json("Hello, World")
}

#[actix_web::main]
async fn main() -> std::io::Result<()> {
    HttpServer::new(|| {
        App::new()
            .service(hello_world)
    })
    .bind("127.0.0.1:8080")?
    .run()
    .await
}

```

<br/>
<h3 align=center>Currently learning</h3>
<div align=center>
<img width="48" height="48" src="https://img.icons8.com/?size=100&id=55205&format=png&color=5B3BCF" alt="csharp logo"/>
<img width="48" height="48" src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ee/.NET_Core_Logo.svg/1200px-.NET_Core_Logo.svg.png" alt="csharp logo"/>
</div>
