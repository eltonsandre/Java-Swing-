# Demonstração uso Substance em java Swing

### dependencias org.pushingpixels
 [substance](https://mvnrepository.com/artifact/org.java.net.substance/substance/6.0)

 [trident](https://mvnrepository.com/artifact/org.pushingpixels/trident/1.3)

 [flamengo](https://mvnrepository.com/artifact/org.pushingpixels/flamengo/5.0)


---

lista todos os temas
```java
 List<SkinInfo> allSkinInfo =  SubstanceLookAndFeel.getAllSkins().values();
```

 seleciona um tema
```java
 SkinInfo skin = allSkinInfo.get(index_tema);
```

Altera o tema e reconstrie a tela com o tema selecionado
```java
 SubstanceLookAndFeel.setSkin(si.getClassName());
 repaint();
 ```