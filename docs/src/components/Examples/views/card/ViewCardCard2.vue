<template>
  <div>
    <div class="ui card">
      <div class="content">
        <div class="right floated meta">14h</div>
        <img class="ui avatar image" src="/images/avatar/large/elliot.jpg"/> Elliot
      </div>
      <div class="image">
        <img class="ui wireframe image" src="/images/wireframe/image.png"/>
      </div>
      <div class="content">
        <span class="right floated">
          <i class="heart outline like icon"/>
          17 likes
        </span>
        <i class="comment icon"/>
        3 comments
      </div>
      <div class="extra content">
        <div class="ui large transparent left icon input">
          <i class="heart outline icon"/>
          <input type="text" placeholder="Add Comment..."/>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ViewCardCard2',
  info: {
    converted: false,
    elementType: 'views',
    element: 'card',
    title1: 'Types',
    title2: 'Card',
    description: 'A single card.',
    model: '    <div class="ui card">\n' +
      '      <div class="content">\n' +
      '        <div class="right floated meta">14h</div>\n' +
      '        <img class="ui avatar image" src="/images/avatar/large/elliot.jpg"/> Elliot\n' +
      '      </div>\n' +
      '      <div class="image">\n' +
      '        <img class="ui wireframe image" src="/images/wireframe/image.png"/>\n' +
      '      </div>\n' +
      '      <div class="content">\n' +
      '        <span class="right floated">\n' +
      '          <i class="heart outline like icon"/>\n' +
      '          17 likes\n' +
      '        </span>\n' +
      '        <i class="comment icon"/>\n' +
      '        3 comments\n' +
      '      </div>\n' +
      '      <div class="extra content">\n' +
      '        <div class="ui large transparent left icon input">\n' +
      '          <i class="heart outline icon"/>\n' +
      '          <input type="text" placeholder="Add Comment..."/>\n' +
      '        </div>\n' +
      '      </div>\n' +
      '    </div>\n',
  },
};
</script>
