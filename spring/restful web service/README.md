https://spring.io/guides/gs/rest-service/

http://localhost:8080/greeting => {"id":1,"xyz":"Hello World!"}
refresh {"id":1,"xyz":"Hello World!"} => {"id":4,"xyz":"Hello World!"}

"id" and "xyz" are the name of methodsin Greeting.java class

    public long getId() {
        return id;
    }

    public String getXYZ() {
        return content;
    }

