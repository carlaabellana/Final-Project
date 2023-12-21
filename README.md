# Final-Project
Marta Garcia: marta.ggonzalez@students.salle.url.edu. 
Carla Abellana: carlabo.abellana@students.salle.url.edu

EXPLICACIÓ PROJECTE:
El nostre projecte consta de un sistema solar.
És a dir, hem utilitzat tres objectes diferents que composen tot el nostre projecte, aquestes son; estrella, pla, esfera.Cadascuna de les instàncies dels objectes consta de la seva textura i llum. 

Quan obrim el projecte, ens trobem el pla principal, el qual veiem el Sol, i els planetes al voltant girant.
Amb el ratolí del ordinador podem anar movent el punt de vista del sistema solar, a més a més, ens podem moure amb les tecles W, S per allunyar-nos i apropar-nos, respectivament i moure cap a la dreta i esquerra amb les tecles A i D respectivament respecte la posició on estem mirant. 


En primer lloc, tenim a la carpeta de "Resource Files" dos fitxers anomenats "shader_sky.frag" i "shader_sky.vert" els quals la seva funció principal és mostrar els gràfics de la skybox. Podíem haver-ho ficat directament al shader.frag amb els demés objectes, però vam creure que seria més senzill implementar-ho per separat i no tenir tantes variables. Seguidament, hem utilitzat tres tipus de transparències: Amb la primera hem tret les parts blanques (anells de saturn) , amb la segona hem agafat una segona textura per treure-li les transparències (atmosfera) i l'última hem incrementat la transparència d'un objecte, en aquest cas l'estrella i l'atmosfera. 
En segon lloc, la Terra té dos mapes: el de relleu i l'especular. I pel que fa l'utilització de la llum hem implementat Blinn-Phong amb la correcta direcció de la llum provinguda del sol. 
Finalment, hem fet que els planetes es moguesin en rotacions diferents, alguns més llargs i d'altres més curts. D'aquesta manera ja contàvem amb els 5 moviments relatius diferents, addicionalment la lluna rota al voltant de la terra. 

En quant a la tècnica avançada d'OpenGL, hem intentat implementar "Bloom" però ens hem trobat amb varies dificultats que no hem sapigut resoldre després de buscar informació per internet i en el learnopengl. Igualment, hem deixat el codi que hem realitzat, ja que hem conseguit parcialment el nostre objectiu amb la creació del framebuffer i la textura bloom, però a l'hora de implementar-ho tot junt és on hem tingut les dificultats. 






