# Práctica GIT

### Lauria Martina

# PracticaGit - Respuestas

---

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?** 

Utilicé `git reset --hard HEAD@{2}` o `git reset --hard 8681303` para volver al commit anterior.


---

**2. ¿Qué comando o comandos utilizaste en el paso12? ¿Por qué?**

Usé `git reflog` para ver el HASH del commit donde quiero volver y `git reset 4fa6c34` para recuperar los archivos en el working copy de ese commit.
Usè `git add donjiuote.md" per aggiungerlo 
y `git commit -m ""Ho riaggiunto l'ultimo file a STYLED" .


---

**3. El merge del paso 13 ¿Causó algún conflicto? ¿Porqué?**

No causa conflicto porque la rama styled ya contiene los commits de la rama master que es la que esta absorviendo.

---


**4. Elmerge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

He hecho el merge tenendome en quenta el contenido de la rama htmlify.

---

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Porqué?**


No, porque la rama "styled" ya contiene lo de la rama "master".

---

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

Usé el comando `git log --graph --decorate --pretty=oneline` .

---


**7. El merge del paso 26,¿Podría ser fast forward?¿Por qué?**

Sí, porque la rama "title" contiene todos los commits de la rama "master", forman una lista y, por lo tanto, sólo tendría que avanzar un commit la rama "master".

---

**8. ¿Qué comando o comandos utilizaste en el paso 27?**


`git reflog`

porque el comando "git reflog" lo usé para ver el HASH del commit

y

`git reset 4fa6c34`

rehacer el commit y recuperar los archivos en el working copy de ese commit.


---

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout . `

---

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

---

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

Usé `git reflog` para ver el HASH del commit inicial y el comando `git reset --hard` .

---

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reset 95a7257`

---

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reset d352591`
