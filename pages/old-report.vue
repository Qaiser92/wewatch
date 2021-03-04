<template>
  <div>
    <v-container>
<v-row
      no-gutters
      style="flex-wrap: nowrap;"
    >
  
      <v-col
        cols="6"
        style="min-width: 100px; max-width: 100%;"
        class="flex-grow-1 flex-shrink-0"
      >
        <!-- <v-card
          class="pa-2"
          outlined
          tile
        >
          I'm 1 column wide and I grow to take all the space
        </v-card> -->
     
          <v-img class="logo" src="https://wewatch.ae/wp-content/uploads/2020/03/logo-web.png"></v-img>
      </v-col>
      
      <v-col
        cols="6"
        style="min-width: 100px;"
        class="flex-grow-0 flex-shrink-1"
      >
        <!-- <v-card
          class="pa-2"
          outlined
          tile
        >
          I'm 5 column wide and I shrink if there's not enough space
        </v-card> -->
        <v-img class="logo_iso" src="https://wewatch.ae/wp-content/uploads/2021/02/Logo-ISO-18788-440.jpg"></v-img>
         <v-img class="logo_iso" src="https://wewatch.ae/wp-content/uploads/2021/02/Logo-ISO-9001-14001-ISO-45001-440.jpg"></v-img>

      </v-col>
    </v-row>
    
    <v-row>

       <v-col
        cols="12"
        style="min-width: 100px;"
        class="flex-grow-0 flex-shrink-1"
        >
      <h1 class="top_h">Daily Safety and Security Report</h1><br>
      <p class="top_h_left">EVENT/PROJECT NAME  </p>
      <p class="top_h_left">KINGDOM OF SAUDI ARABIA</p>
      <p class="top_h_left">02 FEBRUARY 2021 </p>

      <ul class="top_listing">
        <li>John Harris</li>
        <li>Director QHSSE</li>
        <li>UAE: +971 52 216 3038</li>
        <li>KSA: +966 50 604 2270</li>
      </ul>  

       </v-col>

    </v-row>  

       <v-row>

      <v-col
        cols="12"
        style="min-width: 100px;"
        class="flex-grow-0 flex-shrink-1"
        >

      <p class="">Dissemination and Confidentially </p>
      <p class="">This Daily Safety and Security Report should be treated as a commercially sensitive document. Blink Experience should limit and control distribution of this sensitive document and ensure that the original and approved copies are stored in a secure location, in accordance with ISO quality management systems standards and company standard operating procedures (SOPs). </p>
      <p class="" style="color:red;">Confidential </p>


       </v-col>

      </v-row>  


        <v-row>

       <v-col
        cols="12"
        style="min-width: 100px;"
        class="flex-grow-0 flex-shrink-1"
        >

      <h1 class="">1.	Daily Situation Summary <span style="color:red"> (Combined QHSSE) (both) </span> </h1>
      <p class=""> 1.1	Head of Security arrived in Al Qaisumah in the last 24hrs, however Operations Manager requested he return to Riyadh at short notice to support a potential Ministry of Health visit, all passed with no concerns. After speaking with the client relations senior manager, security guards were observed conducting their role of access control. Follow up meeting with Flow Solutions Project Manager (Mahmoud El Sheikh), he was successful in receiving some electrical components for the generators located at KASC. He is also expecting the full delivery of the missing fire extinguishers and spill kits tomorrow, he was also reminded to change the few fire extinguishers that were showing out of date inspections. He is still on track for a more detailed inspection on the 28 Dec 2020 by the Head of Security.  The Project Manager (Mahmoud El Sheikh) remains extremely proactive and eager to fulfil his supplier deliverables.</p>
      <p class="">1.2	Head of Security to conduct another safety inspection on the 28 Dec 2020 with Flow Solutions prior to operational phase. Flow Solutions are only responsible for the Start/Finish location and not any of the bivouac sites.  </p>


       </v-col>

        </v-row>  

         <v-row>

       <v-col
        cols="12"
        style="min-width: 100px;"
        class="flex-grow-0 flex-shrink-1"
        >

      <h1 class="">2.	Event / Project Details  <span style="color:red"> (both) </span> </h1>
       </v-col>
        </v-row>  


  <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">
           Weather
          </th>
          <th class="text-left">
            Wind Strength
          </th>
           <th class="text-left">
            Remarks 
          </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Sunny 25 Degrees</td>
          <td>12 kph</td>
           <td>Rain forecast for the next working day.</td>
          <!-- <td>{{ item.calories }}</td> -->
        </tr>
      </tbody>
    </template>
  </v-simple-table>
<br>  
    <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">
           Design and Build Timings
          </th>
          <th class="text-left">
            Daily Operations man-hour
          </th>
           <th class="text-left">
            Remarks 
          </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>08:00 - 08:00hrs </td>
          <td>12/24hrs </td>
           <td>Two x shifts, day and night operations.</td>
          <!-- <td>{{ item.calories }}</td> -->
        </tr>
      </tbody>
    </template>
  </v-simple-table>

  <br>

  <v-simple-table>
    <template v-slot:default>
      <thead>
        <tr>
          <th class="text-left">
           Contractor Name 
          </th>
          <th class="text-left">
            Staff Numbers
          </th>
           <th class="text-left">
            Shift Pattern
          </th>
          <th class="text-left">
            Daily man-hours
          </th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Mara LLC</td>
          <td>20 </td>
           <td>12 </td>
           <td>240</td>
        </tr>
         <tr>
          <td>Al Laith Scaffolding</td>
          <td>80 </td>
           <td>24</td>
           <td>1920</td>
        </tr>
         <tr>
          <td>VIP Security</td>
          <td>6 </td>
           <td>24</td>
           <td>144</td>
        </tr>
         <tr>
          <td>DB Security LLC</td>
          <td>109 </td>
           <td>24</td>
           <td>2616</td>
        </tr>
      </tbody>
    </template>
  </v-simple-table>




    </v-container>

  </div>
</template>

<script>
export default {
  layout:'error'
}
</script>

<style scoped>

/* .template_body {
 background-image: url("watermark.png");
} */

.logo
{
  width: 350px;
  margin-top:25px;
}
.logo_iso
{
  width: 200px;
  float: right;
  margin:5px;
}
.top_h
{
  font-size: 35px;
  text-align: center;
}
.top_h_left
{
  font-size:25px;
}

ul.top_listing li
{
  display: block;
  font-size: 22px;
  
} 

ul.top_listing
{
padding-left: 0px!important;
}

th.text-left {
    color: #fff!important;
    background-color:#315aa5;
}
td
{
      background: #f1f1f1;
}
</style>
