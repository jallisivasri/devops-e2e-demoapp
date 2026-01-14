package com.devops.demoapp;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@SpringBootApplication
@RestController
public class DemoappApplication {

    @GetMapping("/")
    public String hello() {
        return "Hello from End-to-End DevOps Project 🚀";
    }

    public static void main(String[] args) {
        SpringApplication.run(DemoappApplication.class, args);
    }
}

