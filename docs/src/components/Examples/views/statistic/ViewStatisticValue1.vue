<template>
  <div>
    <div class="ui statistics">
      <div class="statistic">
        <div class="value">
          22
        </div>
        <div class="label">
          Saves
        </div>
      </div>
      <div class="statistic">
        <div class="text value">
          Three<br/>
          Thousand
        </div>
        <div class="label">
          Signups
        </div>
      </div>
      <div class="statistic">
        <div class="value">
          <i class="plane icon"/> 5
        </div>
        <div class="label">
          Flights
        </div>
      </div>
      <div class="statistic">
        <div class="value">
          <img src="/images/avatar/small/joe.jpg" class="ui circular inline image"/>
          42
        </div>
        <div class="label">
          Team Members
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ViewStatisticValue1',
  info: {
    converted: false,
    elementType: 'views',
    element: 'statistic',
    title1: 'Content',
    title2: 'Value',
    description: 'A statistic can contain a numeric, icon, image, or text value',
    model: '    <div class="ui statistics">\n' +
      '      <div class="statistic">\n' +
      '        <div class="value">\n' +
      '          22\n' +
      '        </div>\n' +
      '        <div class="label">\n' +
      '          Saves\n' +
      '        </div>\n' +
      '      </div>\n' +
      '      <div class="statistic">\n' +
      '        <div class="text value">\n' +
      '          Three<br/>\n' +
      '          Thousand\n' +
      '        </div>\n' +
      '        <div class="label">\n' +
      '          Signups\n' +
      '        </div>\n' +
      '      </div>\n' +
      '      <div class="statistic">\n' +
      '        <div class="value">\n' +
      '          <i class="plane icon"/> 5\n' +
      '        </div>\n' +
      '        <div class="label">\n' +
      '          Flights\n' +
      '        </div>\n' +
      '      </div>\n' +
      '      <div class="statistic">\n' +
      '        <div class="value">\n' +
      '          <img src="/images/avatar/small/joe.jpg" class="ui circular inline image"/>\n' +
      '          42\n' +
      '        </div>\n' +
      '        <div class="label">\n' +
      '          Team Members\n' +
      '        </div>\n' +
      '      </div>\n' +
      '    </div>\n',
  },
};
</script>
