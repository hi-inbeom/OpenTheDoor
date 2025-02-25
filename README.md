# OpenTheDoor

## Vue 명명 규칙
1. **Folder Names**: kebab-case
2. **Component Names**: PascalCase
3. **Methods**: camelCase
4. **Props**:
   - Template: kebab-case
   - JavaScript: camelCase
```
<UserProfile user-name="John" />

<script setup>
defineProps<{ userName: string }>();
</script>
```
5. **Emit Events**: kebab-case
6. **Composables**: camelCase
7. **Classes**: kebab-case
8. **Environment Variables**: Uppercase (ALL CAPS)

