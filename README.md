# lainapps
Personal repo of CLI apps written in Rust


Change gitwrapper to mygit?

`cargo run --bin laingit set ../a/path/to/your/private/ssh-key`

`cargo run --bin lainssh git <your-git-command>`

if you want to replace your git for the entire session of your terminal, you can do 

`alias git=laingit`

`cargo build`

`cargo install`


# installed example commands
gitwrapper set ../.ssh/my-personal-private-key

gitwrapper git clone git@...my-personal-project.git

