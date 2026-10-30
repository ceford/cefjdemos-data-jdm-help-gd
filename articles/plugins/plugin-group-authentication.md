<!--
{
    "source": "https://docs.joomla.org/Chunk4x:Extensions_Plugin_Manager_Edit_Authentication_Group",
    "title": "Buidheann Dearbhaidh",
    "description": " ",
    "author": ""
}
-->

## Tuairisgeul na Buidhne

Tha na plugain sa bhuidheann seo air an cleachdadh airson logadh a-steach àbhaisteach luchd-cleachdaidh do na h-eadar-aghaidhean Làraich no Rianaire. ’S e Dearbhadh Joomla an roghainn bhunaiteach. Tha an dòigh *Briosgaid* air a chleachdadh còmhla ris an fheart *Cuimhnich orm* airson logadh a-steach don Làrach a-mhàin. Suidhichear a’ bhriosgaid às dèidh a’ chiad logadh a-steach le aon de na dòighean eile.

## Dearbhadh - Briosgaid

![plugan dearbhaidh briosgaid](../../../en/images/plugins/plugin-group-authentication/01-authentication-cookie-plugin-tab.png)

- **Fad-beatha na Briosgaide** An àireamh de làithean gus an tig a’ bhriosgaid dearbhaidh gu crìch. Faodaidh nithean eile adhbharachadh gun tig i gu crìch nas tràithe na seo. Tha amannan nas fhaide nas lugha de thèarainteachd.
- **Fad na h-Iuchrach** Fad na h-iuchrach a thèid a chleachdadh gus a’ bhriosgaid a chrioptachadh. Tha faid nas fhaide nas tèarainte, ach cuiridh iad maill air coileanadh.

## Dearbhadh - Joomla

Bidh am plugan seo a’ pròiseasadh an dòigh Dearbhaidh Luchd-cleachdaidh bhunaiteach ann an Joomla. Chan eil roghainnean aige.

## Dearbhadh - LDAP

Bidh am plugan seo a’ pròiseasadh Dearbhadh Luchd-cleachdaidh an aghaidh frithealaiche LDAP.

![plugan dearbhaidh ldap](../../../en/images/plugins/plugin-group-authentication/02-authentication-ldap-plugin-tab.png)

- **Òstair** URL an òstair. Mar eisimpleir, `openldap.mycompany.org`.
- **Port** Àireamh a’ phuirt. ’S e 389 an roghainn bhunaiteach.
- **LDAP V3** Co-dhiù a chleachdas an t-òstair seo LDAP tionndadh 3. ’S e LDAP v2 an roghainn bhunaiteach.
- **Rèitich TLS** Co-dhiù a chleachdas an t-òstair seo crioptachadh TLS. Ma tha e air a shuidheachadh gu *Tha*, feumaidh an trafaig uile chun an fhrithealaiche seo agus bhuaithe a bhith air a chrioptachadh.
- **Lean Iomraidhean** Co-dhiù a shuidhicheas tu am bratach LDAP_OPT_REFERRALS gu Tha no Chan eil. Airson òstairean Windows 2003 feumar seo a shuidheachadh gu Chan eil.
- **Dòigh Ùghdarrais** *Ceangail gu dìreach mar chleachdaiche* no *Ceangail agus Lorg*.
- **DN Bunait** DN Bunait an fhrithealaiche LDAP agad.
- **Sreang Lorg** Sreang ceiste a thèid a chleachdadh gus Luchd-cleachdaidh sònraichte a lorg. Thèid am prìomh-fhacal `[search]` a chur an àite leis an logadh a-steach a chuireas an Cleachdaiche a-steach. Mar eisimpleir: `uid=[search]`. Faodar barrachd air aon Sreang Lorg a chur a-steach. Sgaraich gach fear le caractar leth-choloin `;`. Chan eil seo air a chleachdadh ach nuair a thathar a’ lorg.
- **DN a’ Chleachdaiche** Thèid am prìomh-fhacal [username] a chur an àite gu dinamach leis an ainm-chleachdaiche a chuireas an Cleachdaiche a-steach. ’S e sreang eisimpleir a tha ann: `uid=[username], dc=[my-domain], dc=[com]`. Faodar barrachd air aon sreang a chur a-steach. Sgaraich gach fear le caractar leth-choloin `;`. Chan eil seo air a chleachdadh ach ma tha an Dòigh Ùghdarrais gu h-àrd air a shuidheachadh gu *Ceangail gu dìreach mar chleachdaiche*.
- **Ainm-cleachdaiche Ceangail agus Facal-faire Ceangail** Bidh iad seo a’ mìneachadh nam paramadairean ceangail airson ìre lorg an DN. Airson lorg gun urra, fàg an dà raon seo bàn. Airson Ceangal Rianachd, ’s e an *Ainm-cleachdaiche Ceangail* ainm-cleachdaiche cunntais rianachd (mar eisimpleir, *Rianaire*). Anns a’ chùis seo, ’s e *facal-faire a’ cheangail* am facal-faire fhèin airson a’ chunntais rianachd seo.
- **Mapaich: Ainm Làn** Am feart LDAP anns a bheil làn ainm a’ Chleachdaiche.
- **Mapaich: Post-d** Am feart LDAP anns a bheil seòladh puist-d a’ Chleachdaiche.
- **Mapaich: ID Cleachdaiche** Am feart LDAP anns a bheil ID logadh a-steach a’ Chleachdaiche. Airson Active Directory, ’s e `sAMAccountName` a tha seo.
- **Dì-bhugachadh** Cuiridh seo an comas dì-bhugachadh, air a chòdachadh gu cruaidh aig ìre 7.

*Air eadar-theangachadh le openai.com*