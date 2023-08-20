package com.example.prueba.controller;

import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
@RequestMapping("/")
public class testController {

    @GetMapping("saludo")
    public void pruebaTestServidor() {
        System.out.println("Hola Mundo");
    }

    @GetMapping("")
    public String salidaRaiz() {
        return("Hola Mundo");
    }

    @GetMapping("saludoCliente")
    public ResponseEntity<String> pruebaTestCliente() {
        String mensaje = "Hola Mundo";
        return ResponseEntity.ok(mensaje);
    }
}
