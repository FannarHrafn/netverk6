# netverk6

Kóðadæmi frá https://www.linuxjournal.com/content/multiprocessing-python 

Multiprocessing heldur áfram hugsuninni frá https://github.com/FannarHrafn/netverk5 þar sem við fjölluðum um multithreading en multithreading er að gera keyra marga kóða eða sama kóðan á öðruvísi stöðum á sama tíma í einum processor en multiprocessing tekur það einu skrefi lengra og leyfir servers að nýta sér marga processors á sama tíma sem eru líka sjálfir að multithreada svo þetta er server að multitaska marga processors sem eru einnig sjálfir að multitaska með threads, þessar tvær aðferðir koma saman til að mynda a.m.k. alla stóra servers á netinu þar sem að án þessara aðferða þá væru allir servers mun hægari og við mundum ekki vera njóta þess að taka bara nokkrar millisekúndur að ná vefsíðu, það mundi myndast röð af tölvum að bíða eftir að spyrja google um eitthvað til dæmis.
