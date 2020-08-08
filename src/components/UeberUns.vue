<template>
  <div id="ueberuns">
    <v-row>
      <v-col sm="auto" md="6" class="text-justify px-8">
        <v-card flat min-height="900">
          <h1 class="display-2 mb-6">Über Uns</h1>
          <h3 class="mt-4 mb-2 headline blue--text text--darken-4">
            Duncan Taylor
          </h3>
          <p>
            Duncan Taylor wurde 1985 in Derby, England, geboren. Seinen Bachelor of Music im Fach klassische Gitarre absolvierte er zwischen 2006 und 2009 bei Craig Ogden und Gordon Crosskey am Royal
            Northern College of Music (RNCM) in Manchester, England, und schloss dort sein Abschlusskonzert mit der Note 1 ab. Daraufhin nahm er das Masterstudium an der Hochschule für Musik und
            Theater in Hamburg bei Prof. Olaf van Gonnissen und Prof. Klaus Hempel auf, das er im Sommer 2012 mit der Note 1 abschloss.
          </p>
          <p>
            In Großbritannien hat Duncan auf einer Vielzahl von Veranstaltungen konzertiert, darunter in der Venezulanischen Botschaft in London, der Haden Freeman Concert Hall in Manchester und dem
            Bruntwood Theatre, ebenfalls in Manchester. Auch in Deutschland ist er mehrfach im Rahmen von Konzerten und Festivals aufgetreten. Duncan Taylor hat während seines Studiums der klassischen
            Gitarre seine Leidenschaft für lateinamerikanische Musik entdeckt. Im Oktober 2014 begründete er das Ensemble gemeinsam mit einem weiteren Gitarristen und einem Schlagzeuger. Seit Februar
            2017 arbeitet er mit dem Percussionisten Fanis Gioles im ‘Hamburg Combo’ zusammen. Seitdem begeistern die beiden Hamburgs Cafés, Kneipen, Bühnen und Hafenfähren mit ihrer Auswahl aus
            Konzertstücken aus allen Ländern Lateinamerikas, Spanien und erfreuen sich dabei wachsender Beliebtheit.
          </p>
          <h3 class="mt-4 mb-2 headline blue--text text--darken-4">
            Fanis Gioles
          </h3>
          <p>
            Fanis Gioles zählt zu den vielversprechendsten griechischen Schlagzeugern der jungen Genenation. Geboren 1988 in Athen, begann er im Alter von fünf Jahren mit dem Violinspiel, bevor er im
            Alter von zehn mit dem Schlagzeugspielen anfing. Im Jahr 2007 fing er sein Schlagzeugstudium unter den Leitung von Konstantinos Vorissis und Konstantinos Theodorakos (Moschato
            Konservatorium, Acropolis Konservatorium - Kunstzentrum) an. 2013 wurde ihm das Schlagzeug Diplom mit der Note „Ausgezeichnet“ erteilt. Zwischen 2014 und 2017 studierte er an der
            Hochschule für Musik und Theater Hamburg in der Schlagzeugklasse von Prof. Cornelia Monske, und erwarb sein Master mit der Note 1.0 “Ausgezeichnet”.
          </p>
          <p class="mb-12">
            Fanis Gioles gewann zahlreiche Preise bei internationalen und nationalen Wettbewerbe wie den 3. Preis bei den PAS Greece Percussion Competition in 2011, den 2. Preis bei den Griechischen
            Yamaha Wettbewerb Und den DAAD Preis in 2017. Er musiziert zurzeit mit verschiedenen Bands in Deutschland und in Ausland. Seit 2014 wohnt er in Hamburg und arbeitet als Schlagzeuger und
            Schlagzeuglehrer.
          </p>
          <span>Unser <b>YouTube</b> Kanal:</span>
          <v-btn x-large href="https://www.youtube.com/channel/UC7zTuLQ3XWC-lXbacqCjjQg" target="_blank" color="red" icon class="mx-2">
            <v-icon x-large>mdi-youtube</v-icon>
          </v-btn>
          <span>Unsere <b>Facebook</b> Seite:</span>
          <v-btn href="https://www.facebook.com/hamburg.combo/" target="_blank" x-large color="blue" icon class="mx-2">
            <v-icon x-large>mdi-facebook</v-icon>
          </v-btn>
        </v-card>
      </v-col>
      <v-col md="6" class="hidden-sm-and-down px-10">
        <v-img class="mt-2 mx-auto" max-height="800" src="../assets/hamburg_combo.jpg"> </v-img>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: "UeberUns",
};
</script>
