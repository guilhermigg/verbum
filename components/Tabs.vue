<template>
    <section>
        <b-tabs v-model="tabs" position="is-centered">
            <template>
                <b-tab-item label="Antigo Testamento" value="old">
                    <AntigoTestamento />
                </b-tab-item>
                <b-tab-item label="Novo Testamento" value="new">
                    <NovoTestamento />
                </b-tab-item>
            </template>
        </b-tabs>
    </section>
</template>

<script>
import AntigoTestamento from '@/components/TabTestamentos/AntigoTestamento.vue'
import NovoTestamento from '@/components/TabTestamentos/NovoTestamento.vue'

export default {
    components: {AntigoTestamento, NovoTestamento},
    data() {
        return {
            tabs: "old"
        }
    },
}
</script>
