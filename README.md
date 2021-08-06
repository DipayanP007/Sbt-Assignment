# README


## Install sbt
```bash
echo "deb https://repo.scala-sbt.org/scalasbt/debian all main" | sudo tee /etc/apt/sources.list.d/sbt.list
echo "deb https://repo.scala-sbt.org/scalasbt/debian /" | sudo tee /etc/apt/sources.list.d/sbt_old.list
curl -sL "https://keyserver.ubuntu.com/pks/lookup?op=get&search=0x2EE0EA64E40A89B84B2DF73499E82A75642AC823" | sudo apt-key add
sudo apt-get update
sudo apt-get install sbt
```

## Clone the Github Repository

Use the clone command to clone the repository.
```bash
git clone https://github.com/DipayanP007/Sbt-Assignment
```

## Executing the code

##### Change the working directory to the cloned directory
```bash
cd ../Sbt-Assignment
```

##### Run the following commands

```bash
sbt clean
sbt compile
sbt package
```
