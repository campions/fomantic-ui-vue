<template>
  <div :class="classes()">
    <slot />
  </div>
</template>

<script>
import u from '../../lib/util';
// import Enum from '../../lib/enum';
// import Mixins from '../../lib/mixins';

export default {
  name: 'FuiForm',
  mixins: [],
  props: {
    /*
    prop1: { // TODO: Component FuiForm
      type: Boolean,
      description: '',
    },
    prop2: {
      type: String,
      description: '',
      default: '',
    },
    prop3: {
      type: String,
      description: '',
      validator: (value) => {
        return !value || Enum.LeftRight.check(value);
      },
      default: '',
    },
    */
  },
  events: {
    click: {
      description: 'Click event',
    },
  },
  methods: {
    classes: function () {
      return u.concatClasses(
        'form'
      );
    },
  },
};
</script>
