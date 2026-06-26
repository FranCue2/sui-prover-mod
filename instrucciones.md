# Definir variables de ambiente

    export BOOGIE_EXE=/home/linuxbrew/.linuxbrew/bin/boogie && export Z3_EXE=/home/linuxbrew/.linuxbrew/bin/z3

# Usa esta instruccion para testear y ver como se ve el boogie

`¡¡¡Ojo que lo genera en el testing-sui/auction NO donde lo corres!!!`

    cargo run -- -p ./local/test/ -g