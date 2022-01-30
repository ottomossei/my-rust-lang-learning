## Rust-lang-study

docker operation
```bash
# docker start and end
docker-compose up -d --build
docker-compose down
# attach
docker exec -it rust_dev bash
```

create new project
```bash
# create new project
cargo new ${PROJECT_NAME}
# compile
cargo build
# run
cargo run
```

unit build & compile
```bash
# compile
rustc src/main.rs
# run
./main
```