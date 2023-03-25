---
title: Cristina Cornelio
---

# DECK (DECeased Kidney) cross-over program
Work in collaboration with: _A. Nicolò, L. Furian, C. Silvestre, F. Rossi, P. Rigotti, E. Cozzi and F. Neri_

## Using deceased-donor kidneys to initiate chains of living donor kidney paired donations, a new algorithm currently used nationally in Italy.

We designed a flexible algorithm that exploits deceased donor kidneys to initiate chains of living donor kidney paired donations, combining deceased and living donor allocation mechanisms to improve the quantity and quality of kidney transplants. 

The usefulness of the proposed program results undeniable, increasing the overall number of kidneys available for transplantation and, consequently, the aggregate quality and quantity of life of end-stage-renal-disease patients. 

The project is the result of a collaboration between the departments of Mathematics, Economy and Medicine of the University of Padova.

## The Italian strategy

Our procedure has been first approved for a first trial at the local level (Padova University Hospital, the largest center for living donor kidney transplants in Italy), which resulted in the adoption of the new proposed strategy fist locally in Padova and successively nationally. 

The first KP chain initiated by a deceased donor has been performed on March 14, 2018 in Padova and shortly after two more chains respectively of three and four length have been performed at national level showing the benefits of the program.

## The cross-over algorithm

Our algorithm has two different components: 
* **Cycle detection:** This happen when at time *t* a new pair *P* joins the pool. We find a cycle, when exists, in the current pool *Pool-cycle(t)* composed by all the pairs donor/patient that currently part of the program.
* **Chain detection:** This happen when at time *t* a new deceased-donor (*DD*) kidney arrives to the waiting list. We find a chain, when exists, starting with the deceased-donor, in the current pool *Pool-chain(t)* composed by all the pairs donor/patient that currently part of the program and all the *UT* patients (patients with unlikely transplantability: difficult to match). A chain will either terminate with a pair and thus returning a living kidney to the deceased-donor waiting list or with an *UT* patient.
 
<p align="center">
<img src="figures/algorithm_new.png" alt="algorithm_new" width="400"/>
</p>
(*DD kidney:* kidney from a deceased donor; *K:* kidney; *P pairs:* pair of donor/patient; *UT patients:* patients with unlikely transplantability, difficult to match)

## Media coverage and some links

* [Centro Nazionale Trapianti (National Tranplantation Center): DECK cross-over national program announcement](http://www.trapianti.salute.gov.it/trapianti/dettaglioComunicatiNotizieCnt.jsp?lingua=italiano&area=cnt&menu=media&sottomenu=news&id=484)
  * [Technical document 1](https://www.trapianti.salute.gov.it/imgs/C_17_cntPubblicazioni_94_allegato.pdf)
  * [Technical document 2](https://www.trapianti.salute.gov.it/imgs/C_17_cntPubblicazioni_14_allegato.pdf)
* [Announcement of the first deceased donor transplant on March 14, 2018 in Padova - ANSA](https://www.ansa.it/canale_saluteebenessere/notizie/sanita/2018/03/15/in-italia-prima-catena-trapianti-rene-innescata-da-cadavere_82c13bae-a7e3-47d9-b61c-3eb60f891b28.html)

### Press coverage
* [Il Messaggero](https://www.ilmessaggero.it/salute/medicina/trapianti_prima_volta_paziente_riceve_rene_donatore_morto-3608398.html)
* [Rai news](https://www.rainews.it/tgr/puglia/articoli/2018/08/pug-trapianto-rete-da-donatore-deceduto-policlinico-bari-metodo-Deck-f7c20e44-b178-445b-8a82-b76bd771acad.html)
* [Il Gazzettino](https://www.ilgazzettino.it/nordest/padova/trapianti_prima_volta_paziente_riceve_rene_donatore_morto-3608532.html?fbclid=IwAR1pUZ9HLnz6aB11aTWAwDVDcsaGW1uE8eihBMBWlJjovGRO6BmDOmCfgSo)
* [La Repubblica](https://bari.repubblica.it/cronaca/2020/02/26/news/policlinico_bari_trapiante_rene_a_catena-249631369/)
* [Il Corriere del Veneto](https://corrieredelveneto.corriere.it/padova/cronaca/18_marzo_15/italia-prima-catena-trapianto-rene-innescata-cadavere-dfa6d26c-285a-11e8-b8f6-0a9b8a188a71.shtml)
* [Quotidiano sanità](http://www.quotidianosanita.it/scienza-e-farmaci/articolo.php?articolo_id=59945)

## References
* [**Using deceased-donor kidneys to initiate chains of living donor kidney paired donations: algorithm and experimentation**](https://arxiv.org/pdf/1901.02420.pdf), C. Cornelio, L. Furian, A. Nicolò and F. Rossi, Proceedings of the AAAI/ACM Conference on Artificial Intelligence, Ethics and Society (AIES), 2019.
* [**Deceased-donor-initiated chains: first report of a successful deliberate case and its ethical implications**](https://www.researchgate.net/profile/Lucrezia-Furian/publication/332541761_Deceased_Donor-initiated_Chains_First_Report_of_a_Successful_Deliberate_Case_and_Its_Ethical_Implications/links/5f4f5919a6fdcc9879c02cab/Deceased-Donor-initiated-Chains-First-Report-of-a-Successful-Deliberate-Case-and-Its-Ethical-Implications.pdf), L. Furian, C. Cornelio, C. Silvestre, F. Rossi, P. Rigotti, E. Cozzi, F. Neri and A. Nicolò, Transplantation, 2019.
* **Potential gain of utilizing kidneys from deceased donors to initiate “Chain” Kidney Paired donations: quantification of benefit through a real-world retrospective analysis**, C. Cornelio, L. Furian, F. Neri, A. Nicolò, F. Rossi, P. Rigotti, C. Silvestre., Transpl. Int., 2017
