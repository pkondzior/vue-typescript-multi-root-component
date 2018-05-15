<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  functional: true,
  render: function(h, context) {
    return [
      h("tr", [h("td", "foo"), h("td", "bar")]),
      h("tr", [h("td", "lorem"), h("td", "ipsum")])
    ];
  }
});
</script>
