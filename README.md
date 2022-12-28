# Application 7
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|
| HTTP (Hyper Text Transfer Protocol)   |	  	 80 |	Протокол прикладного уровня передачи данных, изначально — в виде гипертекстовых документов в формате HTML, в настоящее время используется для передачи произвольных данных. | 
| DNS (Domain Name System)	            |	53 |	Используется для получения IP-адреса по имени определенного устройства, либо для получения информации о 
пройденном почтой маршруте. |
| NFS (Network File System)		        |     	| Обеспечивает подключение удаленных файловых систем через сеть. Абстрагирован от файловых систем клиента и сервера,
предоставляет прозрачный доступ к файлам, не модифицируя саму программу. |
| FTP (File Transfer Protocol)	    	|	20, 21 | 	Служит для передачи различного программного обеспечения по сети, а также для доступа к удаленным хостам. 
Является протоколом с гарантированной доставкой (или выдачей ошибки). В нем используется множественное подключение. Один канал обеспечивает управление сервером, а остальные непосредственно для передачи данных. |
| IMAP (Internet Message Protocol)	   	|	143 | Обеспечивает доступ к электронной почте. При его помощи, программа получает такой же доступ к почте, хранящейся на сервере, как если бы она находилась на самом устройстве пользователя. |
| SSH (Secure Shell)	                   	|	22	| При его помощи туннелируется TCP-соединение (для передачи данных), обеспечивает удаленное управление операционной системой. Весь траффик внутри его шифруется |
| RTP (Real-time Transport Protocol)		|    	| Передает трафик в режиме реального времени. |
# Presentation 6
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|	
| ICA (Independent Computing Architecture) |	| Закрытый протокол для сервера приложений, определяет спецификацию обмена данными между клиентом и сервером. Также предоставляет серверу ввод клиента, а клиенту графический вывод от серверных приложений. |
| NCP (NetWare Core Protocol)	|	| Сетевой протокол, служащий для обмена между рабочей станцией и файловым сервером. Чаще всего используется в ОС NetWare, но также задействован в Linux, Unix, Windows NT. |
| MIME (Multipurpose Internet Mail Extension) | | Позволяет передавать через электронную почту картинки, звуки и текстовые сообщения. |
| AFP (Apple Filling Protocol) |	548 | Предоставляет доступ к данным устройств, работающих на Mac OS |
| XDR (External Data Representation) | | Основная цель протокола- передача данных между компьютерами с разной архитектурой. Кодирует все данные. |
# Session 5
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|	
| ISNS (Internet Storage Name Service) |	   3205 |	Предназначен для облегчения обнаружения, управления и настройки устройств iSCSI и в сети TCP/IP. |
| L2F (Layer 2 Forwarding) |	               1701	| Служит для создания приватной туннелированной сети через интернет. Сам по себе не обеспечивает безопасность и шифрование, работает в паре с протоколом PPP (Point-to-Point Protocol) |
| PAP (Password Authentication Protocol) |		| Обеспечивает аутентификацию пользователя при помощи пароля, на основе протокола PPP. |
| SMPP (Short Message Peer-to-Peer)	|       2775 |	Открытый протокол для передачи коротких сообщений. Часто используется для массовой рекламной рассылки |
# Transport 4	
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|
| UDP (User Dataram Protocol) |	При его помощи приложения отправляют данные другим пользователям в сети интернет. Не требуется предварительная настройка, установка каналов связи. Нет гарантии доставки, возможны потери. Используется в тех случаях, когда эти потери не критичны, например в стриминговых сервисах. |
| TCP (Transmission Protocol) |	Является протоколом с гарантированной доставкой. Также обеспечивает правильный порядок передачи пакетов и проверку на наличие ошибок. Перед началом передачи данных устанавливает соединение между клиентом и сервером путем трехстороннего рукопожатия. Используется в сервисах, где важна гарантированная доставка данных, например электронная почта или передача данных. |
| DCCP (Datagram Congestion Control Protocol) |	|Протокол, ориентированный на передачу сообщений. Обеспечивает надежное соединение, разрыв, уведомление о перегрузке. |
| SCTP (Stream Control Transmission Protocol) |	Обеспечивает надежную, упорядоченную передачу сообщений, обеспечивает контроль перегрузки. Поддерживает множественную адресацию и резервирование каналов для повышения отказоустойчивости. |
| RSVP (Resource Reservation Protocol) | Служит для резервирования ресурсов в сети при помощи модели интегрированных служб. Приложения могут резервировать при помощи данного протокола необходимые ресурсы либо отказываться от резервирования, когда оно больше не требуется. |
# Network 3
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|
| DDP (Datagram Delivery Protocol) | 4048 |	Доставляет дейтаграмы от сокета к сокету. Используется в сети AppleTalk
| ICMP (Internet Control Message Protocol) | | Используется сетевыми устройствами для отправки сообщений об различных ошибках во время передачи данных. Обычно не используется для передачи данных между системами. |
| IPsec (Internet Protocol Security) | 500, 4500 | Обеспечивает безопасную связь меду двумя устройствами в сетях VPN, путем шифрования пакетов. Поддерживает взаимную аутентификацию пользователей в начале сеанса использует службу криптографической безопасности. |
| IP (Internet Protocol) | | Набор протоколов, который позволяет передавать данные за пределы локальной сети. Функции маршрутизации и межсетевого обмена обеспечивают взаимодействие в сети интернет. |
| PIM (Protocol Independent Multicast) | 103 | Набор протоколов для маршрутизации многоадресной рассылки. Обеспечивают распространение данных по принципу «один к многим», «многие к многим» в сетях интернет, LAN, WAN. |
# Data link 2
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|
| ARP (Address Resolution Protocol) | | Служит для определения МАС-адреса по IP-адресу устройства и таким образом устанавливает с ним связь. |
| EAPS (Ethernet ||Automatic Protection Switching) | | Используется для создания отказоустойчивой топологии путем настройки основного и резервного канала для каждой VLAN. |
| HDLC (High Level Link Control) | | Протокол общего назначения, обеспечивающий либо лучший из возможных, либо надежный канал связи между передатчиком и приемником. Является протоколом с гарантированной передачей данных. |
| IEEE 802.2 | | Обеспечивает логическую связь между программным интерфейсом и компонентами, которые обеспечивают доступ к сети. |
| PPP (Point-to-Point Protocol)	| |Налаживает канал связи напрямую между двумя маршрутизаторами без других промежуточных устройств. Может обеспечивать аутентификацию, сжатие, шифрование данных. |
# Physical 1
| Протокол | Порт | Описание |
|----------------|:---------:|----------------|	
| Bluetooth	| | Технология обеспечения беспроводной двухточечной связи небольшого радиуса действия между двумя различными устройствами. |
| PON (Passive Optical Network) | | Сеть, которая объединяет пользователей при помощи оптоволоконных кабелей . |
| OTN (Optical Transport Network) | | Представляет из себя цифровую оболочку, которая инкапсулирует кадры данных, чтобы обеспечить отправку данных по одному каналу от нескольких источников. Работает через оптоволокно. |
| DSL (Digital Subscriber Line) | | Способ передачи данных по телефонной линии. Выполняется при помощи медных кабелей. Имеет ограниченный частотный диапазон от 20 до 20000Гц. | 
| RS-449 | | Определяет функциональные и механические характеристики интерфейса между данными оконечного оборудования и данными оборудования связи. По сравнению с предыдущим видом RS-232  лучше по быстродействию и дальности, включает новую систему заземления. |