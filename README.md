kubectl -n wedding rollout restart deploy/wedding-web
kubectl -n wedding rollout status deploy/wedding-web
