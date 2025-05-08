# Molecular-analysis

<h1>A thorough Molecular data analysis</h1>

<h2>Description:</h2>
This project involves an in-depth analysis of molecular properties using a dataset containing computational chemistry results. The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Ast. Key objectives of the project include:
<br />
<h2>Objective:</h2>

<br />
<h1>Key Components:</h1>
1.Generate descriptive statistics and correlation matrices for numerical molecular properties.</b>

2.Compare different calculation methods (e.g., DFT-B3LYP) based on average dipole moment and polarizability.</b>

3.Visualize data distributions (e.g., band gap) using histograms and KDE plots.</b>

4.Detect outliers in the band gap using the interquartile range (IQR) method.</b>

5.Parse and analyze charge distribution data to identify molecules with uneven charge spread.</b>

6.Analyze solvent energy trends relative to molecular weight and calculation method.</b>

7.Create and rank custom molecular metrics such as:</b>

Complexity = (Atom Count × Polarizability) / (1 + Rotatable Bonds)

Efficiency Energy = –Solvent Energy / Molecular Weight

8.Filter molecules based on property thresholds:</b>

Band gap > 3.0 eV</b>

Dipole moment between 1.5–2.5 Debye</b>

Polarizability > 25</b>

<h2>Utilities Used:</h2>

- <b>Python</b> 
- <b>Pandas,Matplotlib,Numpy</b>

<h2>Program walk-through:</h2>
<p align="center">
<br/>
<img src="https://media-hosting.imagekit.io/0ee75341842b4af4/Screenshot%20(198)%20a.png?Expires=1841337944&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=imIz2IateWmkNPA5jY5uX8TqSTqoIKtyRdjT-m0qVaSasHHrl7FimHmzGFueQs~QqRXFX7kPAadVazpGUZ6sVJ-gzxNcSMVmK0sVsqwgxVTKKZiLzXIjksIXaQImNYq8dwocg0FVH2rJ2PEZZ8oe3NuBYh3LwnyK6fSsI-7Yj0T6SOeSRm5seTtHaJ~3BMvNbKUKH-qlI7Ai-hrN4Z3hj0Ow2BBVwKBM0sYWBXFadCigThfLvI2IhPqIu40IiYaQGIgrosgbdJK8ictEouvameh365aMC1lb48SJ8JFuHGa1WMm~1OT34O~SiuTzojvE0tHju05p24ilvHloWUlyzA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/09500bc907ae48d8/Screenshot%20(227)%20a.png?Expires=1841338287&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=XsI~Qc5fLojGAXJXfOH-k0wx8wJRHX0AjHijQGoHRyrTZ4S9t5a8x4iFpLFk18EZKZp9uzd1N8M8MABpX0rGEkyy5Cw6kT1M1MvMAZhhvqojxinb5YoWifqLBYkL7kK6hlfgU-CDdtLOBgbZJZcRcHYfDcLORA0wmMEzwHxyXmpBbt~BoRx4Jm3KKmJvVnNDb4NulIEtNcxTFEt2dCEFyhU00hfbvmHJpDZk2ax-Dy9Y9Zrq9SFrcsjjIWpZVh1qtzgMQ8-16RnRy9abI73Kg9Pe-3ig~CxOnZtJ9CInseqPO15NeAVaQpVAr7c1x08Gek7fO9PrC0tYomdbCIYqWA__"/>
<br />
<br />  
<h2>Summary Statistics:</h2>
<strong>1.Mean Temperature Change:</strong> The mean temperature change varies over time, ranging from approximately -0.24°C to 1.52°C. There is a consistent trend of increasing mean temperature change over the years, suggesting a general warming pattern.<br />
<br />
<strong>2.Standard Deviation (Std):</strong> Standard deviation quantifies the spread or dispersion of temperature change values around the mean. A higher standard deviation indicates greater variability in temperature change. For instance, in 2022, the standard deviation is relatively high at 0.67°C, indicating significant variability in temperature change for that specific year.<br />
<br />
<strong>3.Minimum and Maximum Temperature Change:</strong>The minimum and maximum temperature change values denote the lowest and highest observed temperature changes across all years. The minimum temperature change recorded is approximately -1.80°C in 1966, while the maximum temperature change observed is about 3.55°C in 2020.<br /> 
<br />
<strong>4.The average mean temperature</strong> from 1961 to 2022 has increased by approximately 1.159917°C, indicating a warming trend in global temperatures. The standard deviation reflects how much temperature values deviate from the mean temperature. The trend in standard deviation values indicates that the deviation was higher in 2022 compared to 1961.<br /> 
<br />
<strong>5.Percentiles:</strong>such as the 25th, 50th, and 75th percentiles, offer valuable insights into the distribution of temperature change values. For example, the 25th percentile (also known as Q1) signifies the temperature change value that is exceeded by 25% of the dataset. Similarly, the 50th percentile (Q2 or median) denotes the temperature change value surpassed by 50% of the dataset, while the 75th percentile (Q3) indicates the temperature change value exceeded by 75% of the dataset.<br /> 
<br />  
<p align="center">
<br />  
<img src="https://media-hosting.imagekit.io/c257b9040e174561/Screenshot%20(228)%20a.png?Expires=1841338515&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=SHUEvYxp73wZ5uFO8NMecD5eOT~IBSYrTKbJkvQBInMPtY9EwJswHX7CQfceXAXgIIq8nQ6s6hCGGYyy7O2yRvbeOlJQXClS0EmZtga5WIEwywPNdBghoVhFSqJ-KdV3gfwPvh~xatVsnsu4conRMj7QSWDw1lKnyjBAC77onMJL56cJNydIAfyylBp6CSZ1CdpQ69uqJYVFkwYS1nr~EJoKYroxxbkWgi0r5gwecun5xyrWEKcQE38ACJ32FJzyKtOyAMVPLdGNn3MqBvjAnxPCGxKNDfThxnZWPRf6Ty9-OJkLAE4VHD6If33au5WylyM3RX8sM8qK279tlMKbPA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/36253d29732e4e97/Screenshot%20(229)%20a.png?Expires=1841338736&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Aq5XC~hY5XXKsbFYtXbPHZ2erq0DzG2euc2Mtcz1yeZHIcT7G8nPgNBKkq54QKz14zpJvNTiETh8WZO4EYUpzuiMIGQespMo2vka5tOzx8~2ME0j8lwhA88zGzyuasla5TecTIfNxs5nfN8j5yiiWREdpvxXsZqKzQUG5drCJLvLSNZypkDYXp6aA47qj1z6mHCnf5itQDEYD9NYiFeu4q~rGpC29zVPKHg9HrZtWtw9hihSPj~qwlSPgoJxcvjRuA-0WEjsCDvtF1CiY-~~ow7HESqen5pZExwcc7uRiQFGMEydQGdEAVneGSVDHtijGVS-SlzRScMJF9Srl1cVTQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/ba0783eda950490c/Screenshot%20(230)%20a.png?Expires=1841338777&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=yoCD6kTpjIPD8K~aVu6U-twonxWUJGAFhg5IYW8jqNdgcdF7h88tWyBAAB4wVU1~VD6LECfyq4HyILFhiBUUEwj7O5zdHYhxjvEdeaLjW9eXb7vpahrClRMR5ZHbmo~An7CZPfJhOKwNXs8lDYLvYss9GIbY4StoPq0Hxq59YqtbJPUgM07kHkp~c0d-FKg6Oa7H2hzggpDcR12tqzozEz2kfkuTjsptdTxtvmQWpGmM412QRZalooxP4wIU8N0T41JUz0Ib7AGU1NWdh8OLOTuIewhuzbehQYaQQaAg0cW5nhRzIMT7fN6jZ76QAI1NuORxAGGg-pgOa3tJsBxDuQ__"/>
<br />
<br />"/>
<br />
<br />

<h2>Recent Trends:</h2>
This graph is plotted for 62 year gap between Global temperature across all the countries in the dataset. It shows that the temperature has been significantly increased during this time period. The graphs also gives individual variations while all the countries shows a positive temperature effect only Zimbabwe and botswana shows an avearge decrease in temperature during 62 years.<br />
<h2>Implications and Further Analysis:</h2>
<br /> 
The detected warming trend in global surface temperatures carries substantial implications for climate change and its ramifications on ecosystems, weather phenomena, sea levels, and human communities.<br /> 
Additional analysis could delve into unraveling the factors driving the documented temperature fluctuations, evaluating regional discrepancies, and investigating the potential repercussions for biodiversity, extreme weather occurrences, and societal adaptation measures.<br /> 
<br /> 
<p align="center">
<br />
<img src="https://media-hosting.imagekit.io/d35c9af20f36477c/Screenshot%20(231)%20a.png?Expires=1841339002&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=RX60o7EDunKJ3RwsjpisCuN5xgef7KzvLfjjm3VJRQgyLYdt~oWFEfGhkvnEYFz0zL9IpH1OEie93SsMUbAo684Iy5mfQNvTXKTTOo1jbM0t8cewOQi9btKljaGHWSi6wtMK38~1BMVBVIBlduEMWQf~1zBFySOrz-u3IECALJVHCdg93~oM0M~Mk~u2XKRQwE5Bb3hXPlcMWoyITD~lCb36g6GBqZPJiiMt4xutp9YS1sljgPK5n4R~LWhPtV1BJ~i~qy15cdyo363sPzBYktpLCB0o93P5JN4ARIY4O9F1EogCk-JAzMVQRjc~-oYE~of9WvRJhrAtsuSDzh5lAA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/01d9bd3f7cfb47ef/Screenshot%20(232)%20a.png?Expires=1841339035&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=n4~aD6FVrhqhJp9DFoLako~LV7aLfRmhTJPiHlM~7KR~~FXJYU0gGKCNWlrj-i-JVSG41Sz1E3ZGLYTZZHTbW093JPkhiMXNV2C7iIYMQcIgHzx3TCzskavMgoViE2SlCyLdijJp7gsTYvxEWNlqme~8piieQsmtRZPM5d1FOeMw5wdWPz2TP~OX18gi3g0LjbNtC2UA~LLERND8Gv6dSALPu-JWiNiu3KgfYH7Y8wfLptT3hcYQ~huSyxqUMdENaHOdbgHTXEjYCTSW83L5bbRmQUN-ZiqFqAl~jQwISHPhdiz-1PHzHM16kRrhTp1fmjaAcyzAC5dfQKPhoGrBKw__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/46a9f18381f14cd3/Screenshot%20(233)%20a.png?Expires=1841339241&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=uFMUf1QGuu7rCqyvN9l33Ma2OgWAWmXCktCRgXHcTiJwhLiv0Yq0M0hvFjyoSI~kCZSbAnDRXoxIEGHe7T5mH-kQ7zNSXgBZuBptsaLSJ5QMCw4-xChsbJkrMHG-ecwKQwOREH8cSQl8hgQfY5nuzK~BZMnteEkcYelf9djqMgBtCRNxY-GvyJbZcaJKjOSWRejmVs3E-MhkrdKWSIo98ni1Q03dAk~iL392HwReaypj254VxkWoTXMBYB9lZhIsB09rsScFceBlyhugBl7KbolCbAjFJjIJbH7CIN-XKauayURwnfi2tuZgmZiCcbhGBxTlnsp9FStUOdKDh3VFVA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/39216c55707e420a/Screenshot%20(234)%20a.png?Expires=1841339271&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=FA1b-7NyfFB00opayp1aP3SdNEaLP~OysgStrUgMVhE9-eW~uN4a6eDscNcyHtb5rVsjjxDeaoRfmGjSr~IjnrjHRyOx1GQc~Xc15P0cAzBrNhAsyEnmPd~U~Yp5u0mGn7m2H5tFWKaOZdK4jolCzmN7u2pkqn88Ne2ZPDgQh5sqDvoq95z0h2sHXMuoeAQoaGMpCQZBDiONm2ngDKHaU-OL-vSWJwGNHYsjVSOuESu2~9rjRvOhQK9cbJQ1nrZXmWEjCXgDnuN7LOBRlI5Dl1VKgd4tbMYXp2a5lwpRtlrjsvUPHy3Z5UHKPEBmkjR4ZhEPG2Ogd0KgGvxXhj9xlQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/ec449b9f6ffa4b1d/Screenshot%20(235)%20a.png?Expires=1841339295&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=KSNntwNPhc2CPFOf0F~bp1HFSX~LqNnuZ6HhWupMnfhzC5pTjyXvnDlJhf1qJRVQ~CcP7GP-~UsnSu7udq8o2WTy0TjUGn6KpVcfMUcOvQP4olG6MJLv8roLciF8LWGzV3fntqrNUnn1QXHpaEq1jiPk62OyVyaIlYQ~~mavi58G2A348PaJf2KFDYDRpotDUxeK9ux1-YWa4tCTrknfQCXcniki9sSN1EklX1xl4nw3EX58BDy7VwzIN30yyFCgvpHtgBVSJ5VrH1lWo7AKXq2wgOP9-FB5MiuRs4flkKgcxwwYb1s9oEcRrRcmG3tU6KYdRxRrMLzNCqb6K9MdfQ__"/>
<br />
<br />
These graphs shows that there were more negatively contributing countries during 1961 than during 2022. In 2022 there were only two countries which happend to have negative impact on global temperature as compared to 1961 where almost half of the countries in the list had negative impact. This explains why temperature increases with each passing year.<br />
<h2> Trend according to Sub-regions: </h2> 
<br />  
<p align="center">
<br />
<img src="https://media-hosting.imagekit.io/3898f464fe8445e6/Screenshot%20(236)%20a.png?Expires=1841339631&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=NNQVGUg~7bR6-jnFYHYdyLwTe~nLFuWpJL6hOrmv4iaQpjP89dckzUuTj65b-cwON-VCKewTs0JkJ7nMiHJZUmQG1vSaExkWW3n0nv-~VlZ4B5p-J7d04IU9ICIJhWTjiHqKSRHN9PK14fyphlzStF9dndxjrK3q4GyiF9nSOHttUUkI~81ytHhKskJ68Jj7Ie8I2yY144Lozota4MuA8VxyqNDWabfJ40UsNyNEGLwkdl-wmRY6rb2HQvrU78WlDl1MzDAX-FdFF0-~aiE~yeetO~DEiHyuzUJal8CdyJz3r0fRUhgB2ZjzcZ1kb0-xBOGptrjPdbHUfcBZGQ5A8g__"/>
<img src="https://media-hosting.imagekit.io/121f331c617946c2/Screenshot%20(237)%20a.png?Expires=1841339658&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=2CbVweKTpX75b2wKeKMFevQR-YviA~1S3nfZ65D-ASW0DcSRHwxNfV5sz7-T3zAfZiEwWK7umcCBuEiqOqA2plCOXMm-~j5fuW8Pxir2yYii9sGedJ3oBTFBJDLUkVs80521o0qzsAe-j3d8mmXDP8f9igVh~bVVpYyKMxQIB73gAJNkz6KedVvexJpD6eJbEZuzKkG0CtYvg2znKEv6Sya6oUa0qECX7KY50ZutRHRulheX8Sv5yXW-TyZiF5cTPkiia1JzESZK1FbwkueS2xPVeN-Dj9tkV0AtyQmOAGnkGDUW6DE7tbGNYl4o~gHQ7uVFYWFsKnZbRe4ogQB2kw__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/a29c066d79264485/Screenshot%20(240)%20a.png?Expires=1841339685&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=lU19OLby2xaR8Z2cNWlDy54jTpRnLUFB4a6w70rNLjgJVKN4DLWdUOtV1g4xdu~1hYTOKUEj0lJaGGhoO8UK750yL~NkXcQ4K-pO5KEMEvwBSMI9I~JY6Blwwazt9zHSFWw9XqoLnBXEwfhcNDvurMjIMViIVCHfoByOKj81RZPX~853bjxeczMhhYeqgFo4uuKYzhmqNYfDXdPGoXAXc30sg5CmFWtaRlm0bB~s-rvx-QdHl8K4L5pxtZfmbygaJGCPnr2Jc5eMDUf~U3lhZuT4qBdsurg8IzEzMPE9IWJ2IS~SiLZYYzDxwcjoStxp~H~HL8Jhzxrz10zv1evTJQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/85bfa97b70d74c1e/Screenshot%20(239)%20a.png?Expires=1841339721&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Bl70ym6BevtkI3F72rQoZABiGy8Z1LRjzwaiahEVmrHGWWoQtlZprAW44MA1rg~PQa5dFMhAgOcZ418hDYn6PJMmsx1oZ-Vszn4j83uctZhargZ511DU3H6pe9oIRTzoj-L31JgVeqYryN38fiPwxNFnzQpW86F1kIthGvWnsbX1G42gF4XirgdLmHV~uCEWd2cHHbUZdB5Xa5Y4G8jtLXXW-OGksvATOrNHk4TbK7XF4c0Z6G3xjrFPgVyzUq034kVJ7VJTXntLYFlcRyVizXjuJsWQi6rT7En4sAarAtv4nPz5PxoLVKwLHt-lkDsx11BdTWmDZ39z8hKSfJ5W6w__"/>
<br />
<br />

The temperature change across diffrent regions in database is plotted and graph depicts that Europe and Central asia has highest positive impact on warming trend while the curve for middle east and north africa shows anomalies (indicating years of high negative impact), and catches up with the curve for Europe and Central asia in long run while rest of three region shows similar behaviour.Data from the last decade (2010-2022) reveals a sustained period of elevated temperatures, with most years experiencing temperature changes above the average.<br /> 
Also the data from the last decade (2010-2022) indicates a sustained period of elevated temperatures, with most years experiencing above-average temperature changes.
Notably, the years 2014, 2015, 2016, 2019, 2020, 2021, and 2022 stand out as particularly warm years, with temperature changes exceeding 1.4°C in some instances.<br />
<h2>Trend according to income group</h2>
<br />  
<p align="center">
<br />
<img src="https://media-hosting.imagekit.io/85bfa97b70d74c1e/Screenshot%20(239)%20a.png?Expires=1841339721&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Bl70ym6BevtkI3F72rQoZABiGy8Z1LRjzwaiahEVmrHGWWoQtlZprAW44MA1rg~PQa5dFMhAgOcZ418hDYn6PJMmsx1oZ-Vszn4j83uctZhargZ511DU3H6pe9oIRTzoj-L31JgVeqYryN38fiPwxNFnzQpW86F1kIthGvWnsbX1G42gF4XirgdLmHV~uCEWd2cHHbUZdB5Xa5Y4G8jtLXXW-OGksvATOrNHk4TbK7XF4c0Z6G3xjrFPgVyzUq034kVJ7VJTXntLYFlcRyVizXjuJsWQi6rT7En4sAarAtv4nPz5PxoLVKwLHt-lkDsx11BdTWmDZ39z8hKSfJ5W6w__"/>
<img src="https://media-hosting.imagekit.io/f14a182b1f864981/Screenshot%20(241)%20a.png?Expires=1841340145&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=Zp~ZDsvsVpALq0A6m0OBPbep3fvCBOHuUU1IsY6C0jjBrI1~qoTVZBs6dKefDkkSF47bNPUC3YAg3zx4m0yxhnzPrbEL0Mj~tim6ADmusN5EdkwT4OxO8dEVcrm2USAanqQ7PIaN3l1EX9Oeuvi~lC74aCTs839w5PP37ZLitHj76nA6rBUSWAhO7hl~fx22ZFQ9E0blSZ1pyuJi2AXMuN2gDiz11gdleuWoTRrhesf4gAq2V-YXIAIYJTYGkCx7r71rgEbiESI31ihzB2LQS9rsYAXu~Y~tGVgqNN2zgVlOzAV7fVvijqWzwNLyPep9yMGWVVrpjfp2j7SNDqHHnQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/4dbdce6ff4e54d5f/Screenshot%20(242)%20a.png?Expires=1841340185&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=SkZHD2c8Z5du60OgWDIJyi-D5Ywd6h9KI8RG1KmOFQ6YkYv6uXRapXIDBTIMpFTMuJ7S7IeSw8UXc2zaR8zoi1uk1BgISvBoMgDGk-7lLhfpfXC~CItQFHrld3Q9H~uouqDn~M6GUVWQgWKcimdgufSJ8Rqr8qdDky7nbYP7uJGZp9kNJKgAlnyWvIBtvbd0GbZZQzyVNpgUEz68ZxdWxBZId6v1gHX4C6glNGzUoUJq5UL8W4P04DxQXt66kDNOn9r98Wd-G8dhMDazm~WmzFVltRkz~llgSjxSAWlT~ejLF41Vh2yCJhcY7O9Nvts6-gg6SJXB2r3zipz9xJu7eA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/4eb9cda1487b403a/Screenshot%20(243)%20a.png?Expires=1841340229&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=oQ1eJXZgvIjLuHbv8ENRw9zp9K0-1tenTpOVawCKhkDJygWQqSWNMSMfK25VNBVuJMGrfZboZTvnkERUUwA5DrQVecjqzhiqSH2BdWrPOFZfOxyd-85KirBdGfjChvUFPjp3zVrImNxwrZPp-NQu3cqwtE9ttnoL90s88tDnNcm1fzmScu8M7alSIjmWSBLb3Tk5muXmjrp5Xks0Y5GAXGCs4nTnRH6u-mYnuo9o4t-ioLJqe3tsdHENNuUyjBwLnRdrlXx1gSLQSJ5oeKwZgbjh-LA2ZWlUQF6Brubz8eqScJo1Yz-6O~qb6IzGu3W80WPVlDBKOBnwjJtKm8Gy5A__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/45fceeafe59a4a71/Screenshot%20(244)%20a.png?Expires=1841340260&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=VvqNj61eIBzp-WvC3e4yR2A1IY9k0wM0OoLR~Lw~S~NAip9roTsdoVq-BfHXMdk5ox5Rmx926aoBOD94HApXHKQOUDRm5Jh2ry30MxDv81cMoE-UwXj9QYR8VFdYyx95Ka3GXt9bWAz62cMRe2aadyxSuFZXQ1x~INMdiHigRvlLSjWDBZ9BsYWuuh9~D-mdbu0r19jsrmavRV8m5CM4g9oXQ1synLKGFqZJSiAs0k-nkwTlRssaHrYc5nCUEbLTwTqHWPn8VGejPiJ-8tQ98MULzq7SQm1-fAFr6xpPlHNnRWoBlzRVjkTpF4GmDsy5NqTXCMwNBRtK9yD5qQjvJQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/500e1794a9b24d85/Screenshot%20(245)%20a.png?Expires=1841340286&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=EjeeT2cSomMiGVr1WBoziDX2af8CnoIlNBdqwEPCc6h1Ve38-a-p~hsf07lxgvEAK6gZlliS2u4-wyErMPVb5kVBt0a-NVXurq1LvPYkU5p9vbfE~BX7tJZ03pnpo3Z2WN7jwxNWOpY6ftvoA5MCXejlZe0RCVeRO9Ou84Qe2X-9Gs~cAENWbgQwDF4zMyXJwKj1C2~UiWXHEToCVeX5QQN6QOZM2wEFMNwJ27yDN7K6WrU2hrBzcF3~0PzQ4zG7pIzgbddAXecmQ4AdsbxQ1UBvlOx6qUG-SaC-JKI3X6z1howZEbi7Vvx38Bq3IIgCHxCvw5peCGh82bjv1EY3TA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/728cbec3cfe34f7f/Screenshot%20(246)%20a.png?Expires=1841340311&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=sP9u5DPxW93pGxNz4g~bMrinaZrSeevfOPtBRClnuV7bupaftOsdKQIJlQ9uhDZhMp-v0us0z7Wcyt3NN~WfgA3umpVmEXVqJ4J5gwThsgb2Our-2tknNurnoZ3LV7Qfe8FEP5xEObyr2i55qNMLZug3E5Ezp2oBRsJQa5cN6nJWQg7sxP4m82ByS8a3OY3dPJOTi-RfLui~6LhP8fzN1a869h3T5wodpjM0FNnhtvdbuFz452eoO612kLxku79eelrE6PCHkXfpJoa1bLsqGdmpyXVSDfVIM0EalxCAqwBGjF6QjzGzuGfXXI2ipawuqjOd6wi7gWpspsGxONrPNQ__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/5e68a43077334007/Screenshot%20(247)%20a.png?Expires=1841340343&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=0BxOVl9K46kDYZ8-bkqybtaaWDwGxLafE6g9Ney3U5Yh9VVnECaWE1uIrYdLTknhMFUEp4P9ETotvRwwYWEiHfsxVYWv4XXrOP3Zrd8y8rxKoxKr8TLGZMGu4SYjpkqbbuCNn2JkS7Ml2S7NTYKbaHC-p7zKbr0ToRkWMJ-8ImSRNrNFtfKblYZR8prnkdCHRU6RAFqt9DiDzfVeQxWMq3Fz4ot3B94aygJN0itQgSUfLPpYIAXwKwHKsACzQDCZQMegjhcLeKPdmEWqMy9QLgK0WC7X9Cy~MP7cz0~i6VAKDgciHqMyAXEqw5GMJX9zfemFYzkcSfx8e7MXKeJxAA__"/>
<br />
<br />
<img src="https://media-hosting.imagekit.io/883ca2d0e9de4598/Screenshot%20(248)%20a.png?Expires=1841340367&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=0VqZhx62c~s633q4BDrxnOU2Dyfz5oyBgEZV-fl8MzUGHVNd7Dvj3NEqgSNnBBPcDi~r1aYT-BZwPGa~1LXAEhufVnXtJagXs3L8sTAd8zh8T-TQqNSsx0f1nc8uoYtBaDnvhsSUdDgU5ihk2lO491HyHmNXzuorwiw7hgj-6NlQE2SXfkIZQnp0zrf3GXY3~LslG~SeXJ673-c1GIg~AElj3Zq3jexqjFTvKtcQDWe1cKB7ot~yUy28eJxPSfE3vJj8f08tKZuUbWTUk8dZlzm0BwAxXzsTErPLDrgf3Q3XkkibRC3U~2bo4r2x26v0p2dtwDis3Mb7Bg40VYyjdg__"/>
<br />
<br />

Income groups are also observed to have significant impact on the global temperature the bar for high income group is higher than any other group in the observation <br />
<br />
<strong>High-Income Group Impact:</strong> High-income individuals have a larger carbon footprint due to greater consumption, industrial activity, and energy usage.<br />
<strong>Consumption Patterns:</strong> High-income individuals engage in activities with higher emissions, such as frequent air travel and energy-intensive lifestyles.<br />
<strong>Industrial Activity:</strong>Industries catering to high-income markets operate on larger scales and use more energy-intensive production processes, contributing to higher emissions.<br />
<strong>Energy Consumption:</strong> High-income households consume more energy for heating, cooling, and electronic devices, mostly sourced from fossil fuels.<br />
<strong>Policy Implications:</strong> Targeted policies like carbon pricing and renewable energy incentives can help mitigate emissions from high-income groups.<br />
<br />
<h2>Significance:</h2>
This project is important because it helps to understand how the Earth's climate has changed over a long time, 62 years. By looking at big sets of data and using graphs and charts, observations can be made on how things like temperature and weather patterns have changed all around the world.
This information is really useful for people who make decisions about the environment, like government leaders and scientists. They can use what is found out to make better plans to deal with climate change and protect our planet. It's like having a roadmap to help make the right choices to keep the Earth healthy for us and for future generations.
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
