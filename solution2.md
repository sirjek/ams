# Commands used for task 2

1. **docker build -t log-parser .**

2. **docker tag log-parser:latest 322228980454.dkr.ecr.us-east-1.amazonaws.com/log-parser:latest**

3. **docker push 322228980454.dkr.ecr.us-east-1.amazonaws.com/log-parser:latest**

4. **docker run -d -p 8080:80 log-parser**
