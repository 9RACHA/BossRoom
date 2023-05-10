# BossRoom

Na casa proba o Boss Room configurando un Server Relay e un Lobby (Authentication é opcional) mediante os Unity Services. Tes no titorial de Boss Room como facelo: https://docs-multiplayer.unity3d.com/netcode/current/learn/bossroom/bossroom

Unha vez realizado, proba con algún compañeiro a xogar en liña. Forza desconexións para ver se funciona o relay server. Proba o lobby do xeito que mellor che pareza. Se instalaches a Authentication, proba a ter varias builds na mesma máquina.

Entregable:

Informe con capturas do proceso e das probas


## Informe

![image](https://github.com/9RACHA/BossRoom/assets/66274956/21f69677-06ac-440b-bafe-98180c8de231)

![image](https://github.com/9RACHA/BossRoom/assets/66274956/1f72c87c-4fdd-4b06-9d70-8a2b74bc41b6)

![image](https://github.com/9RACHA/BossRoom/assets/66274956/9f1fd63b-4049-4baf-bd8c-6fb79e15d18f)

![image](https://github.com/9RACHA/BossRoom/assets/66274956/88e30f40-44b0-48da-9d81-faafbf8d71a7)

Por defecto el juego no tenia implementado el Relay Server, por eso, al Desconectarse el Host de la partida y pasar unos segundos, la partida acabaria o finalizaria abruptamente sin ninguna opcion de seguir.

Gracias a añadir del Relay server, esto ya no ocurrira ya que si desconecta el Host habra un reintento de conexion con el relay server o se buscara otro Host disponible. 


