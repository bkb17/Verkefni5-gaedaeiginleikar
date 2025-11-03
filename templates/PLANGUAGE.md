# Gæðakrafa lýst í PLanguage 

---

## Merkimiði (TAG)
Reliability.System.Availability

---

## Tilgangur / Ásetningur (AMBITION)
Kerfið skal vera tiltækt og áreiðanlegt yfir allan rekstrartíma til að tryggja að mikilvægar upplýsingar og þjónusta séu alltaf aðgengilegar þegar notendur þurfa á þeim að halda.

---

## Mælikvarði (SCALE)
Hlutfall heildartíma þar sem kerfið er aðgengilegt og virkt fyrir notendur (uptime), mælt í prósentum yfir einn almanaksmánuð.

---

## Mælir / Mæliaðferð (METER)
Kerfisritanir (logs) og eftirlitskerfi (e. monitoring tools) sem skrá niður tímabil þar sem kerfið er niðri eða ekki aðgengilegt, ásamt mælingum á þjónustusvörun (heartbeat signals).

---

## Markmið (GOAL)
Kerfið skal vera aðgengilegt og virkt í að minnsta kosti 99,9% af tímanum yfir einn almanaksmánuð.
(Hagsmunaaðili: Forstöðumaður þjónustukerfa og umönnunar)

---

## Æskilegt (STRETCH)
Kerfið haldi 99,95% aðgengi yfir mánuð í 11 af 12 mánuðum ársins.

---

## Óska (WISH)
Kerfið nái 100% aðgengi á öllum dögum sem ekki eru fyrirfram skilgreindir viðhaldsmánuðir.

---

## Grunnkerfi (BASE PLATFORM)
Linux þjónn með 8 örgjörvakjörnum, 32 GB RAM, SSD diskur, 100 Mbps tenging, keyrt á container-uðum kerfum með sjálfvirkri villuvöktun og viðgerðum (e.g., Kubernetes).

---
