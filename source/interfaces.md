
<table height="700">
    <tr>
        <th><h3> СО </h3></th>
        <th><h3> AS </h3></th>
        <th colspan="9"><h3> Удаленный узел <br/> Интерфейс <br/> Адрес/Маска </h3></th>
    </tr>
    <tr>
        <th> main_border_01 </th>
        <td> 65200 </td>
        <td> Internet <br/> Gig0/0 <br/> 172.1.0.2/30 </td>
        <td> main_border_02 <br/> Gig0/1/0 <br/> 172.16.1.1/30 </td>
        <td> main_asa_01 <br/> Gig0/1 <br/> 172.16.1.5/30 </td>
        <td> mgmt <br/> Lo0 <br/> 172.16.255.1/32 </td>
        <td> branch1_border_01 <br/> Tun13 <br/> 172.16.2.1/30 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_border_02 </th>
        <td> 65200 </td>
        <td> Internet <br/> Gig0/0 <br/> 172.2.0.2/30 </td>
        <td> main_border_01 <br/> Gig0/1/0 <br/> 172.16.1.2/30 </td>
        <td> main_asa_02 <br/> Gig0/1 <br/> 172.16.1.9/30 </td>
        <td> mgmt <br/> Lo0 <br/> 172.16.255.2/32 </td>
        <td> branch1_border_01 <br/> Tun23 <br/> 172.16.2.5/30 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_asa_01 </th>
        <td>  </td>
        <td> main_border_01 <br/> Gig1/1 <br/> 172.16.1.6/30 </td>
        <td> main_core_sw_01 <br/> Gig1/2 <br/> 172.16.1.13/30 </td>
        <td> mgmt <br/> Gig1/2 <br/> 172.16.1.13/30 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_asa_02 </th>
        <td>  </td>
        <td> main_border_02 <br/> Gig1/1 <br/> 172.16.1.10/30 </td>
        <td> main_core_sw_02 <br/> Gig1/2 <br/> 172.16.1.17/30 </td>
        <td> mgmt <br/> Gig1/2 <br/> 172.16.1.17/30 </td>
        <td> main_web_server_01 <br/> Gig1/3 <br/> 172.16.100.1/26 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_web_server_01 </th>
        <td>  </td>
        <td> main_asa_02 <br/> Fa0 <br/> 172.16.100.2/26 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_core_sw_01 </th>
        <td>  </td>
        <td> main_asa_01 <br/> Gig0/1 <br/> 172.16.1.14/30 </td>
        <td> mgmt <br/> vlan100 <br/> 172.17.1.1/25 </td>
        <td> users <br/> vlan200 <br/> 172.17.2.1/24 </td>
        <td> wlan <br/> vlan300 <br/> 172.17.3.1/24 </td>
        <td> voip <br/> vlan400 <br/> 172.17.4.1/24 </td>
        <td> print <br/> vlan500 <br/> 172.17.5.1/25 </td>
        <td> ospf <br/> vlan999 <br/> 172.16.1.21/30 </td>
        <td> mgmt <br/> Lo0 <br/> 172.16.255.3/32 </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_core_sw_02 </th>
        <td>  </td>
        <td> main_asa_04 <br/> Gig0/1 <br/> 172.16.1.18/30 </td>
        <td> mgmt <br/> vlan100 <br/> 172.17.1.2/25 </td>
        <td> users <br/> vlan200 <br/> 172.17.2.2/24 </td>
        <td> wlan <br/> vlan300 <br/> 172.17.3.2/24 </td>
        <td> voip <br/> vlan400 <br/> 172.17.4.2/24 </td>
        <td> print <br/> vlan500 <br/> 172.17.5.2/25 </td>
        <td> ospf <br/> vlan999 <br/> 172.16.1.22/30 </td>
        <td> mgmt <br/> Lo0 <br/> 172.16.255.4/32 </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_access_sw_01 </th>
        <td>  </td>
        <td> mgmt <br/> vlan100 <br/> 172.17.1.11/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_access_sw_02 </th>
        <td>  </td>
        <td> mgmt <br/> vlan100 <br/> 172.17.1.12/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_access_sw_03 </th>
        <td>  </td>
        <td> mgmt <br/> vlan100 <br/> 172.17.1.13/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_ap_01 </th>
        <td>  </td>
        <td> mgmt <br/> Gig0 <br/> 172.17.1.125/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_voip_serv_01 </th>
        <td>  </td>
        <td> mgmt <br/> Fa0/0.100 <br/> 172.17.1.124/25 </td>
        <td> voip <br/> Fa0/0.400 <br/> 172.17.4.254/24 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_wlc_01 </th>
        <td>  </td>
        <td> mgmt <br/> Gig0 <br/> 172.17.1.101/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> main_infra_serv_01 </th>
        <td>  </td>
        <td> mgmt <br/> Fa0 <br/> 172.17.1.126/25 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> PROVIDER </th>
        <td> 65100 </td>
        <td> main_border_01 <br/> Gig1/0/1 <br/> 172.1.0.1/30 </td>
        <td> main_border_01 <br/> Gig1/0/2 <br/> 172.2.0.1/30 </td>
        <td> branch1_border_01 <br/> Gig1/0/3 <br/> 172.3.0.1/30 </td>
        <td> google <br/> Gig1/0/4 <br/> 8.8.8.1/24 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> google </th>
        <td>  </td>
        <td> Internet <br/> Fa0 <br/> 8.8.8.8/24 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> branch1_border_01 </th>
        <td> 65200 </td>
        <td> Internet <br/> Gi0/0 <br/> 172.3.0.2/30 </td>
        <td> mgmt <br/> Gig0/1.100 <br/> 172.18.1.1/26 </td>
        <td> users <br/> Gig0/1.201 <br/> 172.18.2.1/25 </td>
        <td> wlan <br/> Gig0/1.301 <br/> 172.18.3.1/25 </td>
        <td> voip <br/> Gig0/1.401 <br/> 172.18.4.1/25 </td>
        <td> print <br/> Gig0/1.501 <br/> 172.18.5.1/26 </td>
        <td> main_border_01 <br/> Tun31 <br/> 172.16.2.2/30 </td>
        <td> main_border_02 <br/> Tun32 <br/> 172.16.2.6/30 </td>
        <td> mgmt <br/> Lo0 <br/> 172.16.255.10/32 </td>
    </tr>
    <tr>
        <th> branch1_access_sw_01 </th>
        <td>  </td>
        <td> mgmt <br/> vlan100 <br/> 172.18.1.11/26 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
    <tr>
        <th> branch1_ap_01 </th>
        <td>  </td>
        <td> mgmt <br/> vlan100 <br/> 172.18.1.60/26 </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
        <td>  </td>
    </tr>
</table>
