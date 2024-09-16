<template>
    <ThemeSwitcher />
    <div class="card flex flex-col md:flex-row gap-4">
        <InputGroup>
            <Button label="Search" />
            <InputText placeholder="Keyword" />
        </InputGroup>

        <InputGroup>
            <InputText placeholder="Keyword" />
            <Button icon="pi pi-search" severity="warn" />
        </InputGroup>

        <InputGroup>
            <Button icon="pi pi-check" severity="success" />
            <InputText placeholder="Vote" />
            <Button icon="pi pi-times" severity="danger" />
        </InputGroup>
    </div>
</template>
