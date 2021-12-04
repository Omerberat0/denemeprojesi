# denemeprojesi

import 'package:flutter/material.dart';

void main() {
  runApp(Column(
    textDirection: TextDirection.ltr,
    mainAxisSize: MainAxisSize.min,
    crossAxisAlignment: CrossAxisAlignment.start,
    children: [
      Text(
        "Süreyya",
        textDirection: TextDirection.ltr,
        style: TextStyle(
          fontSize: 35.0,
          color: Colors.pink,
        ),
      ),
      Text(
        "Berat",
        textDirection: TextDirection.ltr,
        style: TextStyle(
          fontSize: 35.0,
          color: Colors.yellow,
        ),
      ),
      Text(
        "Mevlüt",
        textDirection: TextDirection.ltr,
        style: TextStyle(
          fontSize: 35.0,
          color: Colors.deepOrangeAccent,
        ),
      ),
      Row(
        mainAxisAlignment: MainAxisAlignment.spaceBetween,
        textDirection: TextDirection.ltr,
        children: [
          Text(
            "Nebahat",
            textDirection: TextDirection.ltr,
            style: TextStyle(
              fontSize: 30.0,
              color: Colors.greenAccent,
            ),
          ),
          Text(
            "Mehmet",
            textDirection: TextDirection.ltr,
            style: TextStyle(
              fontSize: 30.0,
              color: Colors.red,
            ),
          ),
          Text(
            "Sümeyye",
            textDirection: TextDirection.ltr,
            style: TextStyle(
              fontSize: 30.0,
              color: Colors.teal,
            ),
          ),
        ],
      ),
      Row(
        mainAxisAlignment: MainAxisAlignment.spaceEvenly,
        textDirection: TextDirection.ltr,
        children: [
          Icon(
            Icons.home,
            textDirection: TextDirection.ltr,
            color: Colors.deepPurple,
            size: 50,
          ),
          Icon(
            Icons.access_time,
            textDirection: TextDirection.ltr,
            color: Colors.red,
            size: 50,
          ),
          Icon(
            Icons.cake,
            textDirection: TextDirection.ltr,
            color: Colors.blue,
            size: 50,
          ),
        ],
      ),
    ],
  ));
}
