# REPOALEXAPEX09.12.2022
List<String> accountName=new List<String>{'KitcehenAid'};
accountName.add('Apple');
accountName.add('Amazon');
accountName.add('Microsoft');
accountName.add('Dyson');
System.debug(accountName);

List<String> accounts=accountName.clone();
System.debug(accounts);
accounts.add('Bosch');
accounts.add('Samsung');
System.debug('New Account Names:'+accounts);

List<String> accname=new List<String>{'Amazon'};
System.debug(accname);
accname.add('Philips');
accname.add('Samsung');
accname.add('Samsung');
System.debug(accname);
System.debug(accname.get(2));

Set<String> accname1=new Set<String>();
accname1.addAll(accname);
System.debug(accname1);


Map<String,String> ingTrDict=new Map<String,String>();
ingTrDict.put('apple','elma');
ingTrDict.put('table','masa');
ingTrDict.put('computer','bilgisayar');
System.debug(ingTrDict);

Set<String> Ing=ingTrDict.keyset.();
System.debug(Ing);
List<String> Tr=ingTrDict.values();
System.debug(Tr);

/*
COLLECTION
------------
* List  :  - duplikasyona izin var. Aynı eleman birden fazla eklenebilir. index var.  order var.
List<String> variableName = New List<String>();  // boş liste
List<String> variableName = New List<String>{'eleman1','eleman2'}; // elemanlı şekilde 
Ekran çıktısında () ile görülür. 
.add() methodu ile yeni eleman ekleme.  (eleman)  (index, eleman)
[index]
.get(index) elemana ulaşıyoruz.
.size() listenin boyunu eleman sayısını .
.remove(index) elemanı siliyoruz. 
.clear() tüm listeyi siliyoruz.
.contains(eleman) eleman listede varmı yokmu 
.clone() liste tamamen kopyalanır. klonelanır.
= ile alırsam referans oluyor. hangi listeye eleman eklersek ekleyelim 2 sine ekleniyor.
* SET :  - Duplikasyon'a izin vermiyor... İndex yok.  order yok.
Set<String> variableName = New Set<String>();
{} ile gösterilir.
* MAP : 2 SÜTUNLUDUR. <KEY =DATATYPE, VALUE= DATATYPE>   <Id,Sobject> <String,String> <Integer,String>
MAP içinden SET üretebililiriz.  (keyset )
MAP içinden LİST üretebiliriz. (Value) 
Map için Add methodu = PUT (key,value) ile yapılır.
{key=value, key=value,key=value}
*/
