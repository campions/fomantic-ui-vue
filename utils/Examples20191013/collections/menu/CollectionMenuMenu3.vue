<template>
  <div>
    <div class="ui top attached menu">
      <div class="ui dropdown icon item">
        <i class="wrench icon"/>
        <div class="menu">
          <div class="item">
            <i class="dropdown icon"/>
            <span class="text">New</span>
            <div class="menu">
              <div class="item">Document</div>
              <div class="item">Image</div>
            </div>
          </div>
          <div class="item">
            Open...
          </div>
          <div class="item">
            Save...
          </div>
          <div class="item">Edit Permissions</div>
          <div class="divider"/>
          <div class="header">
            Export
          </div>
          <div class="item">
            Share...
          </div>
        </div>
      </div>
      <div class="right menu">
        <div class="ui right aligned category search item">
          <div class="ui transparent icon input">
            <input class="prompt" type="text" placeholder="Search animals..."/>
            <i class="search link icon"/>
          </div>
          <div class="results"/>
        </div>
      </div>
    </div>
    <div class="ui bottom attached segment">
      <img class="ui wireframe image" src="/images/wireframe/paragraph.png"/>
    </div>
  </div>
</template>

<script>
export default {
  name: 'CollectionMenuMenu3',
  info: {
    converted: false,
    elementType: 'collections',
    element: 'menu',
    title1: 'Types',
    title2: 'Menu',
    description: 'A menu',
    model: '    <div class="ui top attached menu">\n' +
      '      <div class="ui dropdown icon item">\n' +
      '        <i class="wrench icon"/>\n' +
      '        <div class="menu">\n' +
      '          <div class="item">\n' +
      '            <i class="dropdown icon"/>\n' +
      '            <span class="text">New</span>\n' +
      '            <div class="menu">\n' +
      '              <div class="item">Document</div>\n' +
      '              <div class="item">Image</div>\n' +
      '            </div>\n' +
      '          </div>\n' +
      '          <div class="item">\n' +
      '            Open...\n' +
      '          </div>\n' +
      '          <div class="item">\n' +
      '            Save...\n' +
      '          </div>\n' +
      '          <div class="item">Edit Permissions</div>\n' +
      '          <div class="divider"/>\n' +
      '          <div class="header">\n' +
      '            Export\n' +
      '          </div>\n' +
      '          <div class="item">\n' +
      '            Share...\n' +
      '          </div>\n' +
      '        </div>\n' +
      '      </div>\n' +
      '      <div class="right menu">\n' +
      '        <div class="ui right aligned category search item">\n' +
      '          <div class="ui transparent icon input">\n' +
      '            <input class="prompt" type="text" placeholder="Search animals..."/>\n' +
      '            <i class="search link icon"/>\n' +
      '          </div>\n' +
      '          <div class="results"/>\n' +
      '        </div>\n' +
      '      </div>\n' +
      '    </div>\n' +
      '    <div class="ui bottom attached segment">\n' +
      '      <img class="ui wireframe image" src="/images/wireframe/paragraph.png"/>\n' +
      '    </div>\n',
  },
};
</script>
