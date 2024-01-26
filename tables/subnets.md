
<table>
    <tr>
        <th width="600" colspan="2"><h3> Горизонтальное соединение бордеров	</h3></th>
    </tr>
    <tr>
        <td width="70%"> main_border_01 - main_border_02 </td>
        <td> 172.16.1.0/30 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> Туннели с филиалами 172.16.2.0/24	</h3></th>
    </tr>
    <tr>
        <td width="70%"> Tunnel 1 </td>
        <td> 172.16.2.0/30 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> Основной канал ядро - ASA - бордер	</h3></th>
    </tr>
    <tr>
        <td width="70%"> main_border_01 - main_asa_01 </td>
        <td> 172.16.1.4/30 </td>
    </tr>
    <tr>
        <td width="70%"> main_asa_01 - main_core_sw_01 </td>
        <td> 172.16.1.12/30 </td>
    </tr>
    <tr>
        <td width="70%"> main_border_01 - main_border_02 </td>
        <td> 172.16.1.20/30 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> Резервный канал ядро - ASA - бордер </h3></th>
    </tr>
    <tr>
        <td width="70%"> main_border_02 - main_asa_02 </td>
        <td> 172.16.1.8/30 </td>
    </tr>
    <tr>
        <td width="70%"> main_asa_02 - main_core_sw_02 </td>
        <td> 172.16.1.16/30 </td>
    </tr>
    <tr>
        <td width="70%"> main_border_02 - main_border_01 </td>
        <td> 172.16.1.20/30 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> DMZ - 172.16.100.0/26	 </h3></th>
    </tr>
    <tr>
        <td width="70%"> web_server </td>
        <td> 172.16.100.0/26 </td>
    </tr>
</table>


<table>
    <tr>
        <th width="600" colspan="2"><h3> MGMT - 172.16.255.0/24 </h3></th>
    </tr>
    <tr>
        <td width="70%"> main_border_01 mgmt lo0 </td>
        <td> 172.16.255.1/32 </td>
    </tr>
    <tr>
        <td width="70%"> main_border_02 mgmt lo0 </td>
        <td> 172.16.255.2/32 </td>
    </tr>
    <tr>
        <td width="70%"> main_core_sw_01 mgmt lo0 </td>
        <td> 172.16.255.3/32 </td>
    </tr>
    <tr>
        <td width="70%"> main_core_sw_02 mgmt lo0 </td>
        <td> 172.16.255.4/32 </td>
    </tr>
    <tr>
        <td width="70%"> branch1_border_01 mgmt lo0 </td>
        <td> 172.16.255.10/32 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> Сеть главного офиса - 172.17.0.0/16	</h3></th>
    </tr>
    <tr>
        <td width="70%"> MGMT - VLAN 100 </td>
        <td> 172.17.1.0/25 </td>
    </tr>
    <tr>
        <td width="70%"> USERS - VLAN 200 </td>
        <td> 172.17.2.0/24 </td>
    </tr>
    <tr>
        <td width="70%"> WLAN - VLAN 300 </td>
        <td> 172.17.3.0/24 </td>
    </tr>
    <tr>
        <td width="70%"> VoIP - VLAN 400 </td>
        <td> 172.17.4.0/24 </td>
    </tr>
    <tr>
        <td width="70%"> PRINT - VLAN 500 </td>
        <td> 172.17.5.1/25 </td>
    </tr>
</table>

<table>
    <tr>
        <th width="600" colspan="2"><h3> Сеть филиала - 172.18.0.0/16	</h3></th>
    </tr>
    <tr>
        <td width="70%"> MGMT - VLAN 101 </td>
        <td> 172.18.1.0/26 </td>
    </tr>
    <tr>
        <td width="70%"> USERS - VLAN 201 </td>
        <td> 172.18.2.0/25 </td>
    </tr>
    <tr>
        <td width="70%"> WLAN - VLAN 301 </td>
        <td> 172.18.3.0/25 </td>
    </tr>
    <tr>
        <td width="70%"> VoIP - VLAN 401 </td>
        <td> 172.16.4.0/26 </td>
    </tr>
    <tr>
        <td width="70%"> PRINT - VLAN 501 </td>
        <td> 172.16.5.0/26 </td>
    </tr>
</table>
