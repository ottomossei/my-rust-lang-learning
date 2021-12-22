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
```bashcd
# create new project
cargo new ${PROJECT_NAME}
# compile
rustc src/main.rs
# run
./main
```